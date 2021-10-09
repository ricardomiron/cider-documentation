# Open source management

## How to install and run Cider

For more information visit CIDER’s documentation below or [github repo](https://github.com/emilylaiken/cider).

## Roadmap for additional features

- **Encryption/Decryption upon consent:** We are adding functionality for personally identifying data to be encrypted prior to consent and only decrypted for analysis after a subscriber has consented. We are also building functionality for the encryption keys to be held by a third party for maximum security and auditing transparency. 

- **Individual explanatinos of predictions:** We plan to implement model-agnostic prediction explanations for mobile phone-based poverty estimates with [LIME](https://www.kdd.org/kdd2016/papers/files/rfp0573-ribeiroA.pdf).

## Ground rules for maintainers and contributers

### Review committee

Bug reports, documentation, and code contribution will be reviewed by [Emily Aiken](https://emilylaiken.github.io/) (UC Berkeley) and [Lucio Melito](https://github.com/LucioMelito) (GiveDirectly). 

### How a contribution is reviewed and accepted

- **To report a bug,** create an issue template on GitHub. Please include a full working example for the bug, including synthetic data if necessary. 

- **To add additional documentation,** create a new branch of Cider’s [documentation repo](https://github.com/LucioMelito/cider-book), with `git checkout -b name-of-new-branch`. Commit your changes and push your new branch to the github repo, and create a pull request with the outline of your changes. Cider can always use additional documentation, so we appreciate your help! 

- **To write code,** please create a new branch of [Cider](https://github.com/emilylaiken/cider/) with `git checkout -b name-of-new-branch`. Commit your changes and push your new branch to the Github repo. Run the tests as indicated in the readme of the repo. Then, create a pull request. In your pull request, please include a description of all changes. For each change, include the files and line numbers that have been changed.

### The types of contributions we'll accept

We will accept contributions to any of the modules in the code; we are particularly interested in engineering additional features and improving machine learning pipelines. 

### When it's an appropriate time to follow up

You can expect a response to an issue or suggestion within three months. We spend about one hour per month on this project.

## Methadology used to build this open-source guide

To build this open source guide, we went through nine frameworks for similar open source guides:

- [Apache Fineract: A Platform for Microfinance](https://github.com/apache/fineract/blob/develop/README.md)
- [Bandicoot: An open-source python package to analyze mobile phone metadata](https://cpg.doc.ic.ac.uk/bandicoot/)
- [CommCare by Dimagi](https://github.com/dimagi/commcare-hq/blob/master/README.md)
- [Flowminder Flowkit](https://github.com/Flowminder/FlowKit)
- [GSMA Innovative Data for Urban Planning](https://www.gsma.com/mobilefordevelopment/wp-content/uploads/2021/07/Innovative-Data-for-Urban-Planning-Opportunities-and-Challenges-Associated-with-Public-Private-Data-Partnerships-SPREADS.pdf)
- [OCHA-Bucky: A COVID-19 model to inform humanitarian operations](https://ocha-bucky.readthedocs.io/en/latest/)
- [SORMAS: Surveillance, Outbreak Response Management and Analysis System](https://github.com/hzi-braunschweig)
- [Thinking Machines](https://github.com/thinkingmachines/ph-poverty-mapping)
- [X-Road](https://github.com/nordic-institute/X-Road-development/blob/master/README.md)

We also consulted with several open-source experts:

- Stephanie Sy | Founder and CEO Thinking machines
- Google.org 
- Stefaan Verhulst | Co-Founder and Chief Research and Development Officer of The Governance Laboratory (GovLab) at New York University












