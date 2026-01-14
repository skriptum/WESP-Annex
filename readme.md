# WESP Annex

Automated Reporting Pipeline for Annex Tables in WESP Report

- uses respective data provider APIs (e.g OECD)
- adjustable base year in all code files (UPDATE FOR NEW YEAR!)
- transparent code (hopefully)



**How to update Country Classifications?**

If there is a new updated regions file (e.g relevant for net-fuel importers / exporters), place it in the `./data` folder, named `Regions.xlsx`



**Replicated Tables**

- Table 9: Commodity prices
- Table 12: Balance of Payments
- Table 13: ODA Sources
- Table 14: ODA uses

The final tables in excel format are in `./output`



**Note**

- some tables may differ ever so slightly from final tables in WESP reports
- some rows were updated completely

= look at the respective code files, at the top there are table-specific notes and checks
