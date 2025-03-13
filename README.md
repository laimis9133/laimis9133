## Hi there 👋

<!--
**laimis9133/laimis9133** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

I'm Laimis Juzeliūnas a DevOps engineer [@oxylabs](https://github.com/oxylabs) working within Data team. I take care of large scale platform builds, do my best to create a self healing infrastructure and enhance overall development experience.  
On my free time I like to contribute back to the open-source community with whatever I find and however I can.

```mermaid

flowchart TD
    classDef me fill:#6495ED,color:white,stroke:#333,stroke-width:2px
    classDef block1 fill:#95A5A6,color:white,stroke:#333
    classDef block2 fill:#5D9CEC,color:white,stroke:#333
    classDef ops fill:#F39C12,color:white,stroke:#333
    classDef dev fill:#2ECC71,color:white,stroke:#333
    classDef current fill:#8E44AD,color:white,stroke:#333,stroke-width:2px
    
    Me(["Me"]) --> |Engineering| Data
    Me --> |Career| Fintech
    
    subgraph Beginning
        Data["Data"]
        Fintech["Fintech"]
    end
    
    Data --> Platforms
    Data --> Pipelines
    Fintech --> Support
    Fintech --> Maintenance
    
    subgraph Past
        Platforms["Platforms"]
        Pipelines["Pipelines"]
        Support["Support"]
        Maintenance["Maintenance"]
    end
    
    Support --> Scaling
    Support --> Automation
    Maintenance --> GitOps
    Maintenance --> IaC
    
    Platforms --> Infrastructure
    Platforms --> LargeScaleData
    Pipelines --> DistComp
    Pipelines --> DevEx
    
    subgraph Current
        subgraph Ops
            Scaling["Scaling"]
            Automation["Automation"]
            GitOps["GitOps"]
            IaC["Infrastructure as Code"]
        end
        
        subgraph Dev
            Infrastructure["Infrastructure"]
            LargeScaleData["Large Scale Data"]
            DistComp["Distributed Computing"]
            DevEx["Developer Experience"]
        end
    end
    
    class Me me
    class Block1 block1
    class Block2 block2
    class Scaling,Automation,GitOps,IaC ops
    class Infrastructure,LargeScaleData,DistComp,DevEx dev
    class CURRENT current

```
