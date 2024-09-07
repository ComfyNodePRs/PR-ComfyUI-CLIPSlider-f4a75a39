# ComfyUI-CLIPSlider

A node to replicate https://huggingface.co/spaces/latentexplorers/latentnavigation-flux

Currently it won't process batches of scales but I'm working on that. I also want to add actual
slider controls if I can find a way to do it in Comfy.



Examples:

These default to using happy/sad, cold/warm, and 'anime girl' as the prompt. they also default to quantanimalcm.


- 1 image:  [json link](https://raw.githubusercontent.com/RhizoNymph/ComfyUI-CLIPSlider/main/workflows/clipslider-1.json)
![](https://private-user-images.githubusercontent.com/82485126/365397278-24c20638-e5df-4a4d-a80f-f391a44d14c4.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjU3MzgyMTksIm5iZiI6MTcyNTczNzkxOSwicGF0aCI6Ii84MjQ4NTEyNi8zNjUzOTcyNzgtMjRjMjA2MzgtZTVkZi00YTRkLWE4MGYtZjM5MWE0NGQxNGM0LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA5MDclMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwOTA3VDE5MzgzOVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTdkMjBiNjM4ZWVhZjNhMTBjYmE3ZWIxODNmYzVjMzM0YzI1Zjk0ZTk4NDEzY2FjZTJhMTc1ODAxMDU0NzNjMTkmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.rzKF42EKZsbhmj7kFRqdwsjW0375C3D3P7VcP_ken28)
- 4 image grid: [json link](https://raw.githubusercontent.com/RhizoNymph/ComfyUI-CLIPSlider/main/workflows/clipslider-4.json)
![](https://private-user-images.githubusercontent.com/82485126/365397275-9e0473c8-4abe-4131-94c3-4c55ee50cd89.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjU3MzgyMTksIm5iZiI6MTcyNTczNzkxOSwicGF0aCI6Ii84MjQ4NTEyNi8zNjUzOTcyNzUtOWUwNDczYzgtNGFiZS00MTMxLTk0YzMtNGM1NWVlNTBjZDg5LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA5MDclMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwOTA3VDE5MzgzOVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTk2MjViODVmNTE0YmY5MGI0M2Y4ODExODgyYWRlNmY2YWEzY2U0MTZhNTY0MGU4YTc5YWRhNDM4MDk4MGYwOGYmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.RDXx1Q1L2d6m9Fyz7NcQM_Yxp84c2ptrbbpK5O-b0YA)
