# Changelog
Sprint is **weekly**. Outside of holidays, sprint call is **every first working day of the week.**

## Initializing 2020/12/21 [Unreleased](https://github.com/Degenics)

- Gitlab initialized ([kevinjanada](http://github.com/kevinjanada))
- Google Cloud Platform initialized ([Decentricity](http://github.com/Decentricity))
- Migrated Gitlab to Github (non-technical considerations applied) ([Decentricity](http://github.com/Decentricity))
- Domain acquired, [www.degenics.com](http://degenics.com) ([Decentricity](http://github.com/Decentricity))
- Website go live, [www.degenics.com](http://degenics.com) ([Decentricity](http://github.com/Decentricity))
- IAM granted, accesses provided, roles defined ([Decentricity](http://github.com/Decentricity))
- UI/UX research: Vitagene, 23andme, Ancestry (Team)
- Storage research: IPFS / Torrent / IPFS+Torrent Research for Whole Genome Sequences (VCF files 1GB++) (Team)
- Payment research: [Transak](http://transak.com) Payment Gateway supported by Consensys (Team)

## Prototyping 2020/12/28 [Unreleased](https://github.com/Degenics)

### Full Changelog

**Architectural decisions:**

- IPFS for storage layer, no Torrent required ([marcondol](http://github.com/marcondol) & ([dedy](http://github.com/aloisius82))
- Deploying on Ethereum testnet ([marcondol](http://github.com/marcondol) & ([dedy](http://github.com/aloisius82))
- Keypair derived from Ethereum keypair ([marcondol](http://github.com/marcondol) & ([dedy](http://github.com/aloisius82) & [kevinjanada](https://github.com/kevinjanada))
- Simple initial UI/UX ([kevinjanada](https://github.com/kevinjanada))
- Consortium / Private Deployment ([Decentricity](http://github.com/Decentricity))
- Marketplace ([Decentricity](http://github.com/Decentricity))
- Smart Contract expires if delivery not done within x days (Agent J, contributor)
- Structure: Nation>City>Lab>GenProduct ([ybobby](http://github.com/ybobby))

**Development**

- Workflow:
    ![/media/20201228Workflow.png](https://github.com/Degenics/degenics-public/blob/main/media/20201228Workflow.png) 
    ([ybobby](http://github.com/ybobby),[marcondol](http://github.com/marcondol) & [dedy](http://github.com/aloisius82))
- Encryption using ethereum address. ([kevinjanada](https://github.com/kevinjanada))
- IPFS connected with encryption, upload / download ability implemented. ([marcondol](http://github.com/marcondol)) 
- UX/UI initialized, keypair & mnemonic process initialized, dashboard initialized. ([kevinjanada](https://github.com/kevinjanada)) Demo is at [/media/20201228UIUX.mkv](https://github.com/Degenics/degenics-public/blob/main/media/20201228UIUX.mkv).

**Revision / Expansion Requests**

- Dashboard expansion with product categories, lab selection, city selection, nation selection (See Workflow)
- Research deanonymizing mechanism (if user requests and provides consent, can print nonymized file)
- Research logistics process & sampling mechanism / UX
- UX tweaks (Jean-Daniel Gauthier, contributor)



## Prototyping 2021/1/4 [Unreleased](https://github.com/Degenics)

### Full Changelog

**Development**

- User onboarding flow 60% implemented ([kevinjanada](https://github.com/kevinjanada)), including:
    - Keygen
    - Private key login
    - Import json keystore
    - Mnemonic login
- User onboarding 40% backlog:
    - Explore onboarding with metamask (see **performance notes**)
    - Anti-frustration features & instructions (when keygen, ensure user has written down key, etc)
    - Progress bars
- Userside core experience 50% implemented (Team), including:
    - Nation, city, lab selection
    - Product selection under labs
    - Payment interface
    - Download and decrypt results when done
- Userside core experience 50% backlog:
    - Payment interface (may use Metamask)
    - More product selections with descriptions (marketplace paradigm)
    - Notifications
    - Instruction page for sampling and sending
    - Template to put on printable envelope with code and lab address
    - Separate buttons to only download certain files (REPORT and/or GENOME type file selection)
- IPFS Upload / Download implemented 60%  ([marcondol](http://github.com/marcondol) & [dedy](http://github.com/aloisius82))
- IPFS backlog 40%:
    - Two flows for the files (one button for REPORT filetype, one button for GENOME filetype, with multiple files allowed for each)
- Labside 50% implemented (Team):
    - Lab can already input user code (anonymous)
    - Lab can already upload file encrypted with user public key
- Labside 50% backlog:
    - Notifications
    - Time / deadline warning to revert with results
    - Instructions for labside user
    - Progress bar



**Demo Video**
    [![Demovid](/media/DegenicsAlpha01.png)](https://www.youtube.com/watch?v=qTyi8Zg8W_A&)

**Performance Notes**
- Team will explore using metamask for a better user experience and performance optimization.

**UX Notes**
- General simplification required for next sprint
- User feedback and anti-frustration features (Jean-Daniel Gauthier, contributor)

**UX Notes, screenshots of Figma mockup with revisions for next sprint (Jean-Daniel Gauthier, contributor):**
    ![1](/media/DA01-1.PNG)
    ![2](/media/DA01-2.PNG) 
    ![3](/media/DA01-3.PNG) 
    ![4](/media/DA01-4.PNG) 
    ![5](/media/DA01-5.PNG)  
