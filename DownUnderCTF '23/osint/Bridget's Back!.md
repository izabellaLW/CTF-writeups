
# Challenge Details

|~|~|
|--------|-------|
|**CTF Name**|_DownUnderCTF 2023_|
|**Challenge Name**| _Bridget's Back!_|
|**Challenge Category**|_OSINT (Open-Source Intelligence)_|
|**Challenge Points**|_100 points_|
|**CTF Date (dd/mm/yyyy)**|_19:30:00 (AEST) 01/10/2023_|

## Prompt
_Bridget's travelling the globe and found this marvellous bridge, can you uncover where she took the photo from?_

NOTE: Flag is case-insensitive and requires placing inside DUCTF{} wrapper! e.g. DUCTF{a_b_c_d_example}

## Attachement(s)
 <img src="https://github.com/DownUnderCTF/Challenges_2023_Public/blob/main/osint/bridgetsback/publish/BridgetsBack.jpg?raw=true" title="Bridget's Back!" alt="Bridget's Back!" width="800" height="600"/>&nbsp;  


# Solution

## Assumed Knowledge
The red bridge is an iconic landmark of San Franciso — _The Golden Gate Bridge_.

## Steps
1. From the aforementioned deduction, I used Google Maps to determine the photograph's location based on the incoming and outgoing traffic. I determined that it was taken on the northern side of GGB.
2. I channelled my inner-Rainbolt GeoGuessr skills and put my focus towards:
     * Terrain
     * Road Infrastructure
     * Lookout Points
3. Still utilising Google Maps, I used the Street View feature. By browsing through street images, I managed to land at **H.Dana Bowers Rest Area** which had a similar view to the photo.

# Flag
Following the flag's syntax, the flag was DUCTF{H._Dana_Bowers_Rest_Area}
