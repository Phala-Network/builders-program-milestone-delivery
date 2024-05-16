# Milestone Delivery :mailbox:

**The invoice has been sent out correctly for this milestone and the delivery is according to the official [milestone delivery guidelines](../../support/milestone-deliverables-guidelines.md).**

* **Application Document:**, please provide a link to the application form or signed contract from the active builders program project (TODO).

https://drive.google.com/file/d/1vXNUXLFqLk7AF5iume1X8hKwHAQANZtw/view?usp=drive_link

**Context** (optional)
We are delivering a pod application that can perform the following tasks: (i) initiate a ZK trusted setup for KZG or Groth16, (ii) Generate a random commitment to a trusted setup ceremony inside SGX/pod, (iii) verify a commitment made to a ceremony. These deliverables fullfil milestones 1 and 2 of the project.

We have also designed a Phat contract that is supposed to integrate with the pods applications. The Phat contract commits state to the Phala blockchain to persist the ceremonies. The ceremony raw data is stored in IPFS given its large size. Overall the Phar contract + pod apps provide the first fully decentralized ZK trusted setup ceremony.

**Deliverables**
> Please provide a list of all deliverables of the milestone extracted from the initial application and a link to the deliverable itself. Ideally all links inside the below table should include a commit hash, which will be used for testing. If you don't provide a commit hash, we will work off the default branch of your repository. Thus, if you plan on continuing work after delivery, we suggest you create a separate branch for either the delivery or your continuing work.
>
> If there is anything particular about any of the deliverables we or a future reader should know, use the respective `Notes` column.

The delivery includes different files and PRs, in order to facilitate the review process, I have linked the relevant files for each milestone.

| Number | Deliverable | Link | Notes |
| ------------- | ------------- | ------------- |------------- |
| 1. | Phat contract |https://github.com/hack-a-chain-software/bazk/tree/phala-delivery/packages/pod-validator| This is the Phat contract responsible for verifying pod computation for both contribution verification (milestone 1) and generation (milestone 2) | 
| 2.  | Gramine Pod | https://github.com/hack-a-chain-software/bazk/tree/phala-delivery/packages/gramine | The pod package creates functionality for both contribution verification (milestone 1) and generation (milestone 2) | 

**Additional Information**
> Any further comments on the milestone that you would like to share with us.
