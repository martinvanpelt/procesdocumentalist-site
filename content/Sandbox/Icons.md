---
title: Icons
icon: "fa-solid fa-diagram-project"
---


Voor de **Hugo Relearn**-thema kun je gebruikmaken van de ingebouwde **Font Awesome**-icons (versie 6). De syntax die je al gebruikt (`{{% icon icon="..." style="..." %}}`) is correct. Hieronder een overzicht van passende icons voor je categorieën, met een mix van **visuele herkenbaarheid** en **professionaliteit** die past bij je procesdocumentatie-expertise.

---

### **Voorgestelde Icons per Categorie**

|Categorie|Icon (Font Awesome 6)|Code voor Hugo Relearn|Toelichting|
|---|---|---|---|
|**Process**|`fa-solid fa-diagram-project`|`{{% icon icon="fa-solid fa-diagram-project" style="primary" %}}`|Visueel proces/stroomdiagramma, past bij BPMN en workflows.|
|**Tools**|`fa-solid fa-tools`|`{{% icon icon="fa-solid fa-tools" style="primary" %}}`|Algemene tools, maar ook specifiek voor software (bv. Confluence, Notion).|
|**Method**|`fa-solid fa-lightbulb`|`{{% icon icon="fa-solid fa-lightbulb" style="primary" %}}`|Symboliseert innovatie/methodiek (past bij je 7x Framework).|
|**Documentation**|`fa-solid fa-book`|`{{% icon icon="fa-solid fa-book" style="primary" %}}`|Klassiek voor documentatie, handleidingen.|
|**Documentation Platform**|`fa-solid fa-server`|`{{% icon icon="fa-solid fa-server" style="primary" %}}`|Voor platforms zoals Confluence/SharePoint (server/opslag).|
|**Templates**|`fa-solid fa-file-lines`|`{{% icon icon="fa-solid fa-file-lines" style="primary" %}}`|Sjabloon/document met regels (herbruikbaarheid).|
|**Example**|`fa-solid fa-magnifying-glass-chart`|`{{% icon icon="fa-solid fa-magnifying-glass-chart" style="primary" %}}`|Voorbeelden/analyses (past bij je praktische benadering).|
|**About**|`fa-solid fa-user-tie`|`{{% icon icon="fa-solid fa-user-tie" style="primary" %}}`|Professionele uitstraling (past bij je freelance rol).|
|**Contact**|`fa-solid fa-envelope`|`{{% icon icon="fa-solid fa-envelope" style="primary" %}}`|Standaard voor contactpagina’s.|
|**Articles**|`fa-solid fa-newspaper`|`{{% icon icon="fa-solid fa-newspaper" style="primary" %}}`|Voor blog/artikelen (past bij je academische achtergrond).|
|**Downloads**|`fa-solid fa-download`|`{{% icon icon="fa-solid fa-download" style="primary" %}}`|Direct herkenbaar voor downloadbare content.|

---

### **Extra Tips voor Hugo Relearn**

1. **Stijlopties**:
    
    - Gebruik `style="primary"` (blauw in Relearn) voor **hoofdicons** (bv. navigatie).
    - Voor **subtiele accenten** kun je `style="light"` of `style="regular"` proberen.
    - Vermijd te veel kleuren: houd het consistent met je thema.
2. **Alternatieven**:
    
    - Voor **"Method"** kun je ook `fa-solid fa-gears` (tandwielen) overwegen als je de nadruk legt op **systeem/structuur**.
    - Voor **"Documentation Platform"** is `fa-solid fa-cloud` (voor cloud-based tools) ook een optie.
3. **Testen**:
    
    - Voeg de icons toe in een **testpagina** en bekijk hoe ze renderen in je Relearn-thema. Sommige icons zien er in kleine formaten beter uit dan andere.
4. **Font Awesome 6**:
    
    - Zorg dat je thema **Font Awesome 6** ondersteunt. In Relearn is dit meestal standaard ingebouwd.

---

### **Voorbeeld in Menu (Hugo Relearn)**

Als je de icons wilt gebruiken in je **menu** (bv. in `config.toml`):

toml

Kopiëren

```
[[menu.main]]
    name = "Process"
    url = "/process/"
    weight = 1
    pre = '<i class="fa-solid fa-diagram-project"></i>'
```

Of direct in Markdown:

markdown

Kopiëren

```
- {{% icon icon="fa-solid fa-diagram-project" style="primary" %}} [Process](/process/)
```