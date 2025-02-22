# The PowerPoint Problem: Common Issues

## Limited data integration
PowerPoint does not support live data connections. Charts and tables rely on static Excel data, requiring manual updates when data changes. This increases the risk of outdated or incorrect information in reports.  

> *Example:* A team receives a corrected dataset after spotting an error. Every affected chart must be manually updated.  

## Manual updates nightmare
Each PowerPoint chart is independent. Any change to scale, content, or formatting must be applied manually to every chart.

### Workflow comparison
| Feature            | PowerPoint | Python (e.g., Matplotlib, Plotly) |
|--------------------|-----------|----------------------------------|
| Auto-updating charts | ❌ No       | ✅ Yes (live data connection)   |
| Data accuracy    | ❌ Error-prone | ✅ Reliable                   |
| Efficiency        | ❌ Slow       | ✅ Automated                  |

## File Size Issues  
PowerPoint charts can become bloated, especially when pasting data with styles. These issues are hard to detect and fix, often requiring manual intervention.  

> **Tip:** PowerPoint stores charts as archives. Changing the file extension to `.zip` allows access to embedded Excel data and metadata. However, editing these files is limited.  

## Inconsistent styling
Unlike coding tools, PowerPoint requires manual formatting, which can lead to inconsistencies. There is no way to apply global style updates to all charts, making visual uniformity difficult to maintain. 

### Common Issues  
- Different scales reduce readability.  
- Inconsistent color schemes cause visual confusion.  
- Misaligned charts due to manual placement. 

## Hard to maintain accuracy
PowerPoint relies on manual adjustment of each element and allows for a large range of adjustments. At the same time, the editor is equipped with multiple *automatic* actions. This combination leads to a plethora of possible errors.

### Common issues
- Pie charts allow totals exceeding 100% but show errors below 100%.  
- Horizontal bar charts reverse data order by default and reset settings when reopened.  
- Data labels wrap automatically, which can distort numerical data but cannot be globally disabled.  

## A selection of PowerPoint specials
Here are some common PowerPoint issues seen in presentations:

to już dla mnie!!!!