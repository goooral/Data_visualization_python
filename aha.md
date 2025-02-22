# The PowerPoint Problem: Common Issues

## Limited data integration
PowerPoint does not support live data connections. Charts and tables use static data from Excel, so users must update them manually when data changes. This can lead to old or incorrect data being shown in reports.

> *Example:* A team receives an updated dataset from the data processing team, after a mistake has been spotted in its previous version. All charts need to be updated by hand, one by one.

## Manual updates nightmare
Each chart in PowerPoint is an individual entity. If there is a decision to change anything about the scale, the contents or the formatting, all charts need to be updated manually, one by one.

### Workflow comparison
| Feature            | PowerPoint | Python (e.g., Matplotlib, Plotly) |
|--------------------|-----------|----------------------------------|
| Auto-updating charts | ❌ No       | ✅ Yes (live data connection)   |
| Data accuracy    | ❌ Error-prone | ✅ Reliable                   |
| Efficiency        | ❌ Slow       | ✅ Automated                  |

## Data bloat
It's possible to accidentally bloat the weight of a powerpoint chart, for example by pasting data with attached styles. Issues like this are difficult to detect and hard to fix. If possible, it's done manually, one by one.

> **Tip:** PowerPoint charts are in fact stored as archives - it is possible to change a chart's extension to *.zip* and open it to access the individual files. You can access the embedded excel file or metadata, such as style files. What you can do with these is limited.

## Inconsistent styling
Unlike coding tools, PowerPoint requires manual formatting, which can lead to inconsistencies. It's not possible to update all charts' styles globally, and changing some parameters requires digging deep into format settings of each individual chart. At the same time, if you pay no attention to the visual consistency of your charts, you may encounter a variety of issues.

### Examples of issues
- Varying scales resulting in issues with readability of data
- Varying color schemes leading to visual chaos
- Misaligned charts due to manual placement

## Hard to maintain accuracy
PowerPoint relies on manual adjustment of each element and allows for a large range of adjustments. At the same time, the editor is equipped with multiple *automatic* actions. This combination leads to a plethora of possible errors.

### Examples of issues
- Charts which are designed to present percentages that sum up to 100% (such as pie charts) allow to insert larger sums, yet present errors when supplied with less than 100%
- Horizontal bar charts automatically present inserted data in the reversed order, it is possible to change it with one checkbox, which, in turn, always reverses to default when you open formatting options
- Data labels wrap automatically. While useful in text, inconvenient while presenting numerical data, percentages. It's not possible to change the setting globally. 

## A selection of PowerPoint specials
Here are some common PowerPoint issues seen in presentations:

to już dla mnie!!!!