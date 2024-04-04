



# UI

```Mermaid
---
title: Widget for Health and Mana 
---
classDiagram
note "This is a UE class"
UUserWidget <|-- AuraUserWidget
AuraUserWidget <|-- WBP_GlobeProgressBar
AuraUserWidget <|-- WBP_Overlay
WBP_GlobeProgressBar <|-- WBP_HealthGlobe
WBP_GlobeProgressBar <|-- WBP_ManaGlobe

WBP_HealthGlobe --* WBP_Overlay
WBP_ManaGlobe --* WBP_Overlay
```