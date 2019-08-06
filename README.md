# vRO Workflow - NSX DFW Rule Hit Count

Export the NSX DFW Rule Hit Counts for all layer 3 DFW firewall rules to a CSV and email this to the user.

Full details of the workflows can be found at [gazflynn.com](https://gazflynn.com/technology/vmware/extracting-nsx-dfw-rule-hit-counts/).

***Updated 6th August, 2019***
- Update the workflow logic to retrieve each rule hit count once the rule ID is found
- Remove unnecessary attributes

***Updated 2nd August, 2019***
- Retrieve all layer 3 sections
- Retrieve each rule from each section and add to Array
- Retrieve the hit count for the array of rule IDs.
