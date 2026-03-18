# Prereq-Diagram-Preview

steps to preview diagram
```bash
npm install

cd ./Prereq-Diagram-Preview

npm run dev

```

modify the class youre viewing:
```jsx
'Prereq-Diagram-Preview/prereq-viewer/src/main.tsx'

<React.StrictMode>
    <App course="MATH_151"/>
</React.StrictMode>
```

modify the state of the user's classes:

```json
'Prereq-Diagram-Preview/prereq-viewer/public/coursesTaken.json'
{
    "taken": [
       "CSCE120 A",
       "MATH251 B",
       "CHEM107 B",
       "MATH151 A",
       "MATH152 A",
       "PHYS 206 A",
       "PHYS 207 A",
       "CHEM117 A",
       "POLS207 A",
       "CSCE121 A",
       "CSCE221 A"
        

    ],
    "enrolled": [
        "CSCE222 A",
        "GEOL101 A",
        "PHYS 216 A"
    ]
}
```
