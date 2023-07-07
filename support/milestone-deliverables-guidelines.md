# Milestone Delivery Guidelines
These are the guidelines to be followed for milestones submitted for evaluation.

## Submission
Please submit all your milestones via PR to the [Phala Builders Program Milestone Delivery repository](https://github.com/Phala-Network/builders-program-milestone-delivery).

## Invoice
Each milestone needs to be reviewed and accepted, after approval you can submit your invoice through email that will be commented in your PR.

## Content
The submission should contain the following information:

- **Name of the builders program project**
- **Link to the open-source code/delivery**
- **[License](#license)**
- **[Documentation](#documentation)**
- **[Formatted code](#formatted-code), according to a set of guidelines**
- **[Testing Guide](#testing-guide)**
- **A list of the [milestone deliverables](#milestone-deliverables)**
- **Any [additional information](#additional-information)**

## License
In order to successfully receive milestone funding for your application it is necessary for the project to have open source code.
We prefer Apache 2.0, but GNU GPL v3.0, MIT or Unlicense are also acceptable. If your delivery comprises multiple repositories, make sure to include the license for each of them.

## Documentation
We value high-quality open source code, but even the most performant code is of little use if it lacks proper documentation.
We require that you document (where applicable):

- API calls.
- Architecture overview and individual component details.
- Algorithms and protocols that are core to your project.
- Any other fundamental building blocks to your technology.

Unless absolutely necessary, make the documentation public as well, ideally as part of the appropriate code repository. This will make it easier for the community to use or adapt your project. Having a full tutorial available is very helpful for all builders who will be using your template.

**Note**: Only focus on your **own** contributions. Do not write detailed explanations of already existing components, e.g. IPFS.

## Formatted code
A codebase that is easy to read is also easy to use. We suggest adopting one style from Day 1 and adhering to it across the entire team.
This helps to keep the commit history clean and facilitates any reviews of the introduced changes.

## Testing Guide
We require that each milestone delivery includes a comprehensive test suite, consisting of:

### A step-by-step guide demonstrating how your code achieves the milestones
Please provide documentation on how to install, compile, run and test the deliverable(s). Make sure to include all necessary prerequisites. Common issues while replicating test results involve, among others, undocumented dependencies, version numbers, local database setups, breaking changes in the main branch since delivery, OS- and browser-specific incompatibilities.

Depending on the deliverable, this could include (but is not limited to)

- How to embed your library in another application.
- How to make example API calls to your service.
- Running your web app.

### Unit tests
As with any quality software project, each logical code component should be testable.

## Milestone Deliverables
Please provide a list of milestone deliverables. This list should closely reflect the list of deliverables agreed on in the Pull Request for the public **Builders Program** application.

Each item in the list should include a link to the deliverable itself, e.g.:

- Google Doc link - make sure anyone with the link has View access
- GitHub repository - include the appropriate file/folder in the link

**Please highlight anything that deviates from the contract** and include further information that you think is relevant to the deliverable, either alongside the appropriate deliverable.

Please ensure the repo has the correct open-source license.

| Number | Deliverable | Link | Notes |
| ------------- | ------------- | ------------- | ------------- |
| 0a. | License | https://github.com/.../LICENSE | ... |
| 0b. | Documentation | ... | ... |
| 0c. | Testing Guide | ... | ... |
| 1. | ... | ... | ... |
| 2. | ... | ... | ... |

## Additional Information
Please add any additional comments that you consider relevant for the evaluation.
