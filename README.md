# Criminal Justice Education Website

An interactive educational website exploring the critical pillars of criminal procedure: Arrest, Search and Seizure, and Interrogation and Confession. This project uses Bootstrap 5 and Font Awesome for a modern, responsive design with a professional "Justice Theme."

## Features

### 📚 Educational Content
- **Arrest**: Definition, probable cause, arrest warrants, warrantless arrests, use of force standards, and arrest statistics
- **Search and Seizure**: Fourth Amendment, search warrants, exclusionary rule, plain view doctrine, stop and frisk, and warrant exceptions
- **Interrogation and Confession**: Custodial interrogation, Miranda rights, voluntary vs. coerced confessions, false confessions, and interrogation science

### ⚖️ Landmark Court Cases
The website includes detailed information on major Supreme Court cases:

**Arrest Cases:**
- Terry v. Ohio (1968) - Stop and frisk
- Payton v. New York (1980) - Warrantless home arrests
- Graham v. Connor (1989) - Use of force standards
- Tennessee v. Garner (1985) - Deadly force during arrest

**Search and Seizure Cases:**
- Mapp v. Ohio (1961) - Exclusionary rule
- Katz v. United States (1967) - Reasonable expectation of privacy
- United States v. Ross (1982) - Automobile exception
- Arizona v. Gant (2009) - Search incident to arrest

**Interrogation & Confession Cases:**
- Miranda v. Arizona (1966) - Miranda warnings
- Escobedo v. Illinois (1964) - Right to counsel during interrogation
- Rhode Island v. Innis (1980) - Definition of interrogation
- Michigan v. Mosley (1975) - Re-initiating questioning
- Colorado v. Connelly (1986) - Involuntary confessions
- Yarborough v. Alvarado (2004) - Custody determination

### 🎨 Design Features
- **Justice Theme**: Deep navy backgrounds with gold accents
- **Responsive Layout**: Works on desktop and mobile devices
- **Interactive Modals**: Click court case names for detailed information
- **Visual Aids**: Images, charts, tables, and embedded videos
- **Card-Based Content**: Modern column layout for easy reading

## File Structure

```
Crim/
├── index.html          # Main landing page
├── Home.html           # Home page with welcome content
├── aresst.html         # Arrest section
├── SAS.html            # Search and Seizure section
├── confession.html     # Interrogation and Confession section
├── style.css           # Main stylesheet
├── home.css            # Home page specific styles
├── README.md           # This file
└── images/
    ├── Arrest/         # Arrest-related images
    ├── Confession/     # Confession-related images
    └── SAS/            # Search and Seizure images
```

## Adding Photos and Videos

### Photos
- Place image files in the appropriate subdirectory under `images/`
- Supported formats: JPG, JPEG, PNG, GIF, WEBP, AVIF
- Update the `src` attributes in the HTML files to match your image filenames

### Videos
- The website uses embedded YouTube videos
- To replace a video, update the `src` attribute in the iframe:
  ```html
  <iframe src="https://www.youtube.com/embed/VIDEO_ID?si=..." ...></iframe>
  ```

### Image Suggestions
- Arrest: Flowchart, timeline, probable cause diagram
- Search and Seizure: Warrant comparison chart, privacy diagram, exclusionary rule graph
- Confession: Miranda breakdown, interrogation techniques chart

## Color Scheme

The site uses a professional "Justice Theme":

| Color | Hex Code | Usage |
|-------|----------|-------|
| Deep Navy | #0d1b2a | Main background |
| Navy Blue | #1b263b | Secondary background |
| Gold | #ffc107 | Accents, highlights, borders |
| Amber | #ffb300 | Secondary gold |
| Teal | #009688 | Secondary accent |
| Cyan | #00acc1 | Additional accent |
| Slate | #2c3e50 | Card backgrounds |
| Light | #ecf0f1 | Primary text |
| Muted | #bdc3c7 | Body text |

## Running the Website

1. Open `index.html` in any modern web browser
2. Navigate using the menu to explore different sections
3. Click on court case names to view detailed modal information

## Technology Stack

- **HTML5**: Semantic markup
- **CSS3**: Custom styling with CSS variables
- **Bootstrap 5.3**: Responsive framework
- **Font Awesome 6.4**: Icon library
- **Google Fonts**: Montserrat font family

## License

This educational project is for learning purposes.

