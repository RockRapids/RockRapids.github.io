# COGNITIVE TOOLS FOR FREE CITIZENS OF LYON COUNTY

In this bright year 2025, the digital landscape resembles nothing so much as ancient Rome—magnificent, crowded, and utterly resistant to architectural innovation. Platform loyalties are settled with the finality of religious conversion. Another app? ***Meh*** ... Save your breath and development time -- nobody cares; nobody wants to go back to 2010.

Our project operates on a principle the military discovered millennia ago: **INTELLIGENCE wins wars**, not the nice ass or app that's ridden into battle. We're building an API-first cognitive framework using Rust—because when information is ammunition, we don't tolerate delays, misfires or insecure information. Our implementation slashes latency to by orders of magnitude because in intelligence work, yesterday's data or something you wanted work on fifteen minutes ago is as useful as yesterday's weather report.

Some say that the human brain didn't evolve to process exabytes, but the fundamental failing in really revolutionizing the design of AI assistants and user interface latency has been treating humans as passengers on goat trains rather than pilots that fight. Our free, open source extensible system creates a true symbiosis—the machine processes data at machine speeds while the human makes decisions at human levels. The Tauri/Rust/Svelte interface, forked from [GitButler](https://gitbutler.com/) and tweaked slightly for our use cases, branches like evolutionary paths because the universe doesn't offer single solutions—it offers **spectrums** of diverse possibilities. 

A citizen that works with their options to create something unique is FREE; a passive customer with convenient choices fed by a recommendation engine is being herded and groomed for harvest. The difference matters to those who prefer to die fighting like General Nathaniel Lyon, the namesake of Lyon County, rather than grovel on their knees accepting what is offered.

## About the Project

The Rock Rapids community applications ecosystem consists of eight interconnected web applications, each addressing specific aspects of community life:

- [Rockrapids.INFO](https://rockrapids.github.io/FOSS/0/): The central hub and top-level gateway to all Rock Rapids applications
- [Rockrapids.ART](https://rockrapids.github.io/FOSS/1/): Information about arts, crafts, creative endeavors that showcases Rock Rapids citizens.
- [Rockrapids.FUN](https://rockrapids.github.io/FOSS/2/): Highlighting recreational activities and entertainment options, especially in Rock Rapids.
- [Rockrapids.GUIDE](https://rockrapids.github.io/FOSS/3/): Providing civic, school, church, Sheriff, EMT/Fire and public service information
- [Rockrapids.SHOP](https://rockrapids.github.io/FOSS/4/): Featuring retail promotions and shopping events of Rock Rapids merchants/vendors.
- [Rockrapids.STORE](https://rockrapids.github.io/FOSS/5/): Listing marketplace items and products for sale that showcase locally available items.
- [Rockrapids.WORK](https://rockrapids.github.io/FOSS/6/): Connecting people with employment opportunities
- [Rockrapids.XYZ](https://rockrapids.github.io/FOSS/7/): Coordinating volunteer activities and recognition

## Design Philosophy

Our approach focuses on three core principles:

1. **Reuse what works**: We prioritize established, proven solutions rather than reinventing systems unnecessarily
2. **Connect and fill gaps**: We focus on integrating existing resources and addressing unmet needs
3. **Build for maintainability**: We create simple, sustainable solutions that future volunteers can easily maintain and improve

For a deeper understanding of our approach, please review these key documents:
- [Integrate Necessary Existing and Future Datastores](https://rockrapids.github.io/communication/2025/03/31/RockRapidsApps-Step0-1.html)
- [Design For Maintainability and Extensibility](https://rockrapids.github.io/communication/2025/03/31/RockRapidsApps-Step0-4.html)
- [Technical Architecture Overview](https://rockrapids.github.io/communication/2025/03/29/RockRapidsApps.html)

## Technical Architecture

The applications are built using:

- **Frontend Framework**: [Remix](https://remix.run/)
- **Data Management**: Polyglot persistence strategy (PostgreSQL, MongoDB, Redis)
- **Deployment**: [Fly.io](https://fly.io/)
- **Repository Structure**: Monorepo with shared packages

This architecture was selected for its maintainability, performance, and alignment with the skill sets available in our volunteer community.

## Getting Started

### For Users

Visit [RockRapids.INFO](https://rockrapids.info) to access the central hub for all Rock Rapids community applications.

### For Local Developers

1. Attend one of our monthly contributor meetings in Rock Rapids (see [RockRapids.INFO](https://rockrapids.info) for schedule)
2. Review our [Contributing Guidelines](CONTRIBUTING.md)
3. Set up your local development environment:

```bash
# Clone the repository
git clone https://github.com/rockrapids/community-apps.git

# Install dependencies
cd community-apps
npm install

# Start the development server
npm run dev
```

### For Communities Looking to Fork This Project

If you're interested in adapting this ecosystem for your own community:

1. Feel free to fork this repository
2. Customize the applications to meet your community's specific needs
3. Consider the maintenance requirements and ensure you have local volunteers who can sustain the system
4. We recommend preserving the design philosophy of simplicity and maintainability

## Contributing

This project is designed to be built and maintained by volunteers from the Rock Rapids community. If you're a resident of Rock Rapids or the surrounding area and would like to contribute, please:

1. Review our [Contributing Guidelines](CONTRIBUTING.md)
2. Familiarize yourself with our [Code of Conduct](CODE_OF_CONDUCT.md)
3. Join us at an upcoming in-person meeting or training session

We value local participation to ensure our applications truly serve the specific needs of Rock Rapids.

## Deployment

The applications are hosted on Fly.io, with detailed deployment instructions available in the [deployment documentation](docs/deployment.md).

## Project Status

This project is in active development. See the [Issues](https://github.com/rockrapids/community-apps/issues) page for current work items and the [Projects](https://github.com/rockrapids/community-apps/projects) page for our roadmap.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

We gratefully acknowledge the contributions of all Rock Rapids volunteers who have helped build and maintain these applications. Special thanks to:

- Our dedicated corps of volunteer developers and designers
- Community organizations who have provided feedback and testing

## Contact

Project Coordinator: Mark Bruns - [MarkBruns@MarkBruns.com](mailto:MarkBruns@MarkBruns.com)

For general inquiries, please attend one of our monthly community meetings (details on [RockRapids.INFO](https://rockrapids.info)).
