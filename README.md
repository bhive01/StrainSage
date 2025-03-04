# StrainSage: The Open Source Brewing Yeast Database

A community-driven database of brewing yeast strains and their relationships, backed by evidence.

## About This Project

StrainSage aims to be the most comprehensive and accurate resource for homebrewers and professional brewers to understand brewing yeast strains and their similarities or differences. Unlike other yeast comparison charts, StrainSage:

- Documents the **evidence** behind each claimed relationship
- Uses a **community-driven approach** with version control
- Provides **structured data** that can be easily visualized or integrated into brewing software
- Records both **confirmed relationships** and **disputed relationships**

## How to Use This Database

### As a Brewer

1. **Browse the web interface** to explore yeast strains and their relationships
2. **Search for substitutes** when your preferred strain isn't available
3. **Explore the evidence** to understand how confident you can be in a substitution
4. **Contribute your knowledge** by submitting changes via GitHub

### As a Developer

1. **Clone the repository** to access the structured data
2. **Use the JSON Schema** to validate your own applications
3. **Contribute scripts** for data visualization or conversion
4. **Build integrations** with brewing software

## Data Structure

The database is organized into two main components:

1. **Strain Data** (`/strains/`): Individual YAML files containing technical specifications for each yeast strain
2. **Relationship Data** (`/relationships/`): YAML files documenting the relationships between strains, along with supporting evidence

This separation allows for independent updates to either strain information or relationship claims.

## How to Contribute

We welcome contributions from homebrewers, professional brewers, yeast labs, and brewing scientists!

### Adding or Updating a Yeast Strain

1. Fork the repository
2. Create or modify the strain YAML file in the `/strains/` directory
3. Ensure it validates against our schema
4. Submit a pull request with a clear description of your changes

### Adding or Updating a Relationship

1. Fork the repository
2. Modify the appropriate relationship file in the `/relationships/` directory
3. Include evidence to support your claim
4. Submit a pull request explaining your reasoning

### Guidelines for Evidence

Strong evidence includes:
- Manufacturer statements (even indirect ones)
- Scientific papers with genetic analysis
- Controlled brewing experiments with side-by-side comparisons
- Expert opinions from brewing scientists or professional brewers

Weaker evidence includes:
- Anecdotal reports
- Forum discussions without controlled experiments
- Similar specifications without supporting testing

## Project Roadmap

- **Phase 1** (Current): Data structure and initial population
- **Phase 2**: Web interface for browsing the database
- **Phase 3**: Interactive visualization of strain relationships
- **Phase 4**: API for integrating with brewing software
- **Phase 5**: Mobile app for on-the-go yeast substitution reference

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT) - see the LICENSE file for details.

## Acknowledgments

- Thanks to David M. Taylor for the original [Yeast Master](https://docs.google.com/spreadsheets/d/16XRUloO3WXqH9Ixsf5vx2DIKDmrEQJ36tLRBmmya7Jo/edit?gid=1846233287#gid=1846233287) spreadsheet that inspired this project
- Thanks to all contributors who have added their knowledge to this database
- Thanks to the homebrewing community for supporting open knowledge sharing
