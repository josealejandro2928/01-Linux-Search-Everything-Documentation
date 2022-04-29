# Linux Search Everything
<img src="https://user-images.githubusercontent.com/37028825/166054685-9f56c077-52c2-4af1-ba6b-a2e87cde847b.png" height="140"/>
A faster and more flexible file browser for **Linux**, offering rich capabilities such as case sensitivity, **regular expression** based search, search by selecting multiple file types, selection of **BFS algorithms** based on multi threads, control of how deep the algorithms go, choice of custom files to not be taking into account in the search process to improve the search speed and more features.

## Stack selected and architecture
It was made using the electron framework. The UI was created with Reactjs version 18, using the new concurrency capabilities in this new release. Redux library was used as the global state feature.
For the features related to file search and shell command execution, Nodejs was used.
The project is in the process of getting started, my goal is to achieve the capabilities of the windows "everything" software. 
In this version we are not using indexing. But we are exploiting the multitasking capabilities offered by Nodejs to try to perform a search in the file tree as fast as possible. I use child_process, spawn, fork, and worker_threads.

![1-home-view](https://user-images.githubusercontent.com/37028825/166050292-9f306649-1593-48b2-96f4-4a1933ccc9b3.png)


### Installers links on Drive

<https://drive.google.com/drive/folders/1BBPZhR-4YVGxHIWIV_JBFh-GS5-TREDv?usp=sharing>

### get the .deb package

<https://drive.google.com/uc?id=1Cc0GkkmN90em-FVCqWGWuJjOnih1JeeY&export=download>

### get the .rpm package

<https://drive.google.com/uc?id=1ZqsD89e1gh-VamQqFEfkqlRj_8xYwM0I&export=download>

### get the .zip package

<https://drive.google.com/uc?id=1UlRHTkF48yNpftZ2UDtuLdG28QlCh4ob&export=download>
