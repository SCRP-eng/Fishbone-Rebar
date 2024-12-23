
# Ishikawa Diagram for Final Rebar Issues

```mermaid
graph TD
    Final_Rebar["Final Rebar"]
    Final_Rebar --> Quantify["Quantify"]
    Final_Rebar --> Supplier["Supplier"]

    Quantify --> WM_Calc["Not yet waste management calculation"]
    Quantify --> Format["Make a format or schematic to describe rebar substitution"]
    Quantify --> Subst_Work["Make sure substitution works"]

    Supplier --> Cut_Bend["Not supply cut and bend"]
    Supplier --> Coupler["Not supply coupler"]

    WM_Calc --> QS["Add QS Personnel"]
    Format --> QS
    Subst_Work --> SPV["Add SPV Personnel"]

    Cut_Bend --> New_Supplier["Add another supplier to make coupler and threading"]
    Coupler --> New_Supplier
    Coupler --> Bored["Add to scope bored piling contractor to conduct cut and bend (fabrication)"]
```

---

## Notes
This Ishikawa diagram identifies issues and solutions for the "Final Rebar" problem using Mermaid.js.
Ensure Mermaid rendering is enabled on GitHub for proper visualization.
