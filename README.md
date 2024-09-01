# Installatie en gebruik Robot Framework

## Installatie Robot Framework

### Gebruik van PIP
In je terminal, voer het volgende in om Robot Framework te installeren
`pip install robotframework`

Om te controleren of de installatie correct is uitgevoerd, voer in je terminal het volgende in:
`robot --version`

Als de installatie correct is uitgevoerd dien je een robot versie terug te krijgen als antwoord.
Voor het gebruikmaken van libraries die in de testen voorkomen dien je de volgende libraries via PIP te installeren:
`pip install robotframework-requests`

### Uitvoeren van testscripts
Om de suite te draaien dien je naar de directory te navigeren (via je terminal) en het volgende te executeren:
`robot naam_file_test.robot`
