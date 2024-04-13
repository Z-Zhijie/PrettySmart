# experiment

The experiment data for our empirical study and detection results.

## empirical_study

- `require_categorization_200_100.xlsx`: the categorization of require statements that occurs >= 200/100 times.

- `ifthen_categorization_100.xlsx`: the categorization of if-then statements that occurs >= 100 times.

- `mapping_require_address.json`: `mapping<statement, list_of_contracts>`. The mapping relationship between each require statement and a list of smart contract addresses where the require statement occurs. Each contract could be find in [etherscan.io](https://etherscan.io/) by the contract address.

## detection_result

- `Smartbugs_labeledRes.xlsx`: the 673 detection result of PrettySmart on Smartbugs-wild dataset, as well as our manual inspection labels.

- `Smartbugs_comparedTools.xlsx`: the detection result of the compared tools on Smartbugs-wild dataset, as well as our manual inspection labels for the 1195 (331+44+237+284+45+254) sampled contracts.

- `ReportedVulnerability_Res.xlsx`: the detection result of PretteySmart and compared tools on the *ReportedVulnerability* dataset.
