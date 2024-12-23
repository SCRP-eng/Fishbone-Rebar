
# Ishikawa Diagram for Final Rebar Issues

```mermaid
graph TD
    Final_Rebar["Final Rebar"]
    Final_Rebar --> Quantify["Quantify"]
    Final_Rebar --> Supplier["Supplier"]

    Quantify --> WM_Calc["Waste Management Calculation (Not Yest Establised)"]
    Quantify --> Format["Make a format or schematic to describe rebar substitution"]
    Quantify --> Subst_Work["Make sure subtitution works for rebar fabrication"]

    Supplier --> Cut_Bend["Not supply cut bend and coupler"]
   WM_Calc --> QS["Add QS Personnel"]
    Format --> QS
    Subst_Work --> SPV["Add SPV Personnel"]

    Cut_Bend --> New_Supplier["Add another supplier to make coupler and threading"]
    New_Supplier--> Thread["Add dedicated or temporary fabrication area for threading"]
    Thread--> Mechine["Add mechine cutting and thread area for threading"]
    
    

    
    Cut_Bend --> Bored["Add to scope bored piling contractor to conduct cut and bend (fabrication)"]
```

---

## Notes
This Ishikawa diagram identifies issues and solutions for the "Final Rebar" problem using Mermaid.js.
Ensure Mermaid rendering is enabled on GitHub for proper visualization.
