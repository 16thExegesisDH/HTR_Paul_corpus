# HTR_Paul_corpus

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


# Guideline for Transcription

| **Sign**             | **Example**                                                                                          | **Source**                                  | **Transcription** | **Unicode** |
|----------------------|-----------------------------------------------------------------------------------------------------|--------------------------------------------|-------------------|-------------|
| Pilcrow              | <img src="https://github.com/FourbeFlo/Lambertus/blob/main/images/piedDeMouche_1.jpg" alt="Pillcrow" width="85" height="47"> | [e-rara, p.11](https://doi.org/10.3931/e-rara-6338) | ¶                 |     `U+00B6`        |
| Semicolon (shaped)   | <img src="https://github.com/FourbeFlo/Lambertus/blob/main/images/semi-colon%20shapped.png" alt="semi-colon" width="27" height="48"> | ?                                            | q́;                | q `U+0071` + acute `U+0301` <br> ; `U+003B`             |

# Encoding Problem

### Reading Hidden Characters in Junicode on eScriptorium


| Complexe Character | Encoding Failure | Encoding Success |
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
   - Apply the style to the **e-Scriptorium** domain for better visualization of Junicode characters.

---


