# vRO Workflow - NSX DFW Rule Hit Count

Export the NSX DFW Rule Hit Counts for all layer 3 DFW firewall rules to a CSV and email this to the user.

Full details of the workflows can be found at [gazflynn.com](https://gazflynn.com/technology/vmware/extracting-nsx-dfw-rule-hit-counts/).

Updated 6th August, 2019
- Update the workflow logic to retrieve each rule hit count once the rule ID is found, instead of storing all rules in an array.
