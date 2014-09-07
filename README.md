# Ändringar
- Flyttade in all SASS i en egen mapp, lite enklare organisering bara.
- Flyttade _header.scss och _content.scss in i en modules/ submapp istället för i tools/, mer logiskt
- La till variabler på värden som används ofta, för att det enkelt ska kunna ändras på ett ställe
- Förenklade nestingen, ett #id eller .class räcker oftast, om det inte är för att en .class ska bete sig olika när den är inom en två olika element. t.ex .info-text ska vara annorlunda i #main-header mot i #main-content.
- Gjorde en mixin av en kodsnutt som upprepades på flera ställen, närmare bestämt opacitet hover effekten.
- Lite smågrejer jag kan ha missat.