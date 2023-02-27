
How I ran this:

1. Since I had other things running locally on port 8080, I edited docker-compose.yaml to change the ports config to 7070:8080

2. docker-compose pull

3. docker-compose up
~                    
Homepage screencap:

<img width="983" alt="image" src="https://user-images.githubusercontent.com/29604888/221662751-6f5db46e-811d-4964-bc06-4b415620e78e.png">

Note that I have required approvals for pull requests against my forked repo:

<img width="1130" alt="image" src="https://user-images.githubusercontent.com/29604888/221663485-057ac677-3c3f-4fff-ba8e-2a7e72436404.png">

Commits directly against masters are not good practice - that is why we have pull requests, so that repo owners can have propsed new code tested and approved prior to merge. For the output.md file, since I am the repo owner, and since it does not add executable code, I directly merged into master :)

