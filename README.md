# HTR_Paul_corpus
A

![characters badge](badges/characters.svg) ![regions badge](badges/regions.svg) ![lines badge](badges/lines.svg) ![files badge](badges/files.svg)

# Guideline for Segmentation

The main documentation  is here: [Annotation Guide on GitHub](https://github.com/DEFI-COLaF/LADaS/blob/main/AnnotationGuide.md).

## Examples of Specific Cases in Our Corpus

### Legend
- **RunningTitleZone**: pink
- **MainZone:Head**: yellow
- **MainZone:P**: dark green
- **MainZone:P#Continued**: light blue
- **NumberingZone**: rosa (specific examples provided)
- **DropCapitalZone**: dark viola
- **QuireMarkZone**: viola

### 3. Examples

| Description | Example |
| -------- | ------- |
| **RunningTitleZone**: pink <br/> **MainZone:Head**: yellow <br/> **MainZone:P**: dark green <br/> **MainZone:P#Continued**: light blue <br/> **NumberingZone**: rosa for "section 12" and "102" <br/> **QuireMarkZone**: viola | <img src="/pictures/Bucer_Eph_1.png" width="300"/> |
| **RunningTitleZone**: pink <br/> **DropCapitalZone**: dark viola <br/> **MainZone:Head**: yellow <br/> **MainZone:P**: dark green <br/> **MainZone:P#Continued**: light blue <br/> **NumberingZone**: rosa for "456", "II", "III" <br/> **QuireMarkZone**: viola | <img src="/pictures/Bucer_Rm_1.png" width="300"/> |
| **RunningTitleZone**: pink for "VII" (Epistle number) and "Col" (Epistle name) <br/> **MainZone:Head**: yellow <br/> **MainZone:P**: dark green <br/> **MainZone:P#Continued**: light blue <br/> **NumberingZone**: rosa for "7", "8", "184" | <img src="/pictures/Lefevre_1.png" width="300"/> |
| **RunningTitleZone**: pink for "COM" <br/> **DropCapitalZone**: dark viola <br/> **MainZone:Head**: yellow <br/> **MainZone:P**: dark green <br/> **MainZone:P#Continued**: light blue <br/> **NumberingZone**: rosa for "1", "C4", "D4", "5", "6" | <img src="/pictures/Lefevre_2.png" width="300"/> |
| **RunningTitleZone**: viola <br/> **MainZone-ListItem**:green <br> **MainZone:Head**: red <br/> **MainZone:P**: orange <br> **NumberingZone**: blue <br> **QuireMarkZone**: dark blue | <img src="/pictures/entry.png" width="300"/> |
| **TitlePageZone**: light viola <br/> **MarginTextZone-ManuscriptAddendum**: red <br> _for the manuscript annotation around the text_ <br> | <img src="/pictures/TitlePage.png" width="300"/> |


# Guideline for Transcription

| **Sign**             | **Example**                                                                                          | **Source**                                  | **Transcription** | **Unicode/Junicode** |
|----------------------|-----------------------------------------------------------------------------------------------------|--------------------------------------------|-------------------|-------------|
| Pilcrow              | <img src="https://github.com/FourbeFlo/Lambertus/blob/main/images/piedDeMouche_1.jpg" alt="Pillcrow" width="85" height="47"> | [e-rara, p.11](https://doi.org/10.3931/e-rara-6338) | ¶                 |     `U+00B6`        |
| Semicolon (shaped)   | <img src="https://github.com/FourbeFlo/Lambertus/blob/main/images/semi-colon%20shapped.png" alt="semi-colon" width="27" height="48"> |                                       | <img src="pictures/mysteria_litterae/que_acute_semicolon2.png" alt="que accentue" width="60" height="67">               | q `U+0071` + acute `U+0301` <br>  `Junicode (F1AC)`             |
|cumque abreviation | <img src="pictures/mysteria_litterae/cumque_abreviation.png" alt="cumque" width="27" height="48"> | | <img src="pictures/mysteria_litterae/que_ligature.png" alt="cumque" width="76" height="45"> | Junicode (00E8BF)+tilde (000303)|
|tur abreviation  | <img src="pictures/mysteria_litterae/tur_abreviation.png" alt="tur" width="27" height="48"> || <img src="pictures/mysteria_litterae/tur_online.png" alt="cumque" width="48" height="75">| Junicode(000303)  + t unicode|

# Encoding Problem
Some characters in eScriptorium use the Junicode font, and a suitable interface is needed for reading them.

### Reading Hidden Characters in Junicode on eScriptorium

| Original state | Encoding Failure | Encoding Success |
|:----------------:|:-----------------:|:----------------:|
| <img src="./pictures/stylus/qligature.png" width="80"> |  <img src="./pictures/stylus/encodingfail.png" width="80"> | <img src="./pictures/stylus/encoding_working.png" width="80">|

---

### Steps to Resolve Encoding Issues with Stylus:

1. **Use Google Chrome:**  
   Ensure you are using Chrome as your web browser. The following steps require the Stylus extension.

2. **Download the Stylus Extension:**  
   Install Stylus from the Chrome Web Store:  
   [Stylus Extension](https://chromewebstore.google.com/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)

3. **Upload the MUFI Style for eScriptorium:**  
   Download the MUFI style from this link:  
   [MUFI for eScriptorium](https://userstyles.world/style/3915/mufi-for-escriptorium)

4. **Implement and Apply the Style:**  
   - Open the Stylus extension in Chrome.  
   - Upload the downloaded MUFI style.  
   - Apply the style to the **e-Scriptorium** domain
---

<img src="./pictures/stylus/change_stylecss.png" > <br/>
<img src="./pictures/stylus/plugin_stylus.png" > <br/>
     


