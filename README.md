# vRO Workflow - NSX DFW Rule Hit Count

Export the NSX DFW Rule Hit Counts for all layer 3 DFW firewall rules to a CSV and email this to the user.

Full details of the workflows can be found at [gazflynn.com](https://gazflynn.com/technology/vmware/extracting-nsx-dfw-rule-hit-counts/).

### Sample Output

![Image of Sample Report](https://github.com/GaryFlynn/vro-workflows-nsx-dfw-rule-hit-count/raw/master/nsx-rule-hit-count-report-output.PNG)

### Change Log

***Updated 19th August, 2019***
- Added the below fields to the CSV output. Logged is an optional field where the requester is prompted to include this field or not.
  - Disabled (TRUE / FALSE)
  - Action (allow / deny)
  - Logged (TRUE / FALSE)
  - Sources (any or array of sources)
  - Destinations (any or array of destinations)
  - Services (any or array of services, along with the protocol)

***Updated 6th August, 2019***
- Update the workflow logic to retrieve each rule hit count once the rule ID is found
- Remove unnecessary attributes
- Added email CSV as an optional requirement

***Updated 2nd August, 2019***
- Retrieve all layer 3 sections
- Retrieve each rule from each section and add to Array
- Retrieve the hit count for the array of rule IDs
