# Linux Search Everything
<img src="https://user-images.githubusercontent.com/37028825/166054685-9f56c077-52c2-4af1-ba6b-a2e87cde847b.png" height="140"/>

A faster and more flexible file browser for <strong>Linux</strong>, offering rich capabilities such as case sensitivity, <strong>regular expression</strong> based search, search by selecting multiple file types, selection of <strong>BFS algorithms</strong> based on multi threads, control of how deep the algorithms go, choice of custom files to not be taking into account in the search process to improve the search speed and more features.
<br/>
<br/>
![1-home-view](https://user-images.githubusercontent.com/37028825/166050292-9f306649-1593-48b2-96f4-4a1933ccc9b3.png)


## Stack selected and architecture
It was made using the [Electron framework](https://www.electronjs.org/). The UI was created with [Reactjs](https://reactjs.org/) version 18, using the new concurrency capabilities in this new release. [Redux](https://redux.js.org/) library was used as the global state feature.

For the features related to file search and shell command execution, [Nodejs](https://nodejs.org/) was used.The project is in the process of getting started, my goal is to achieve the capabilities of the windows "everything" software. 
In this version we are not using indexing. But we are exploiting the multitasking capabilities offered by Nodejs to try to perform a search in the file tree as fast as possible. I use [child_process](https://nodejs.org/docs/latest-v17.x/api/child_process.html), [spawn](https://nodejs.org/docs/latest-v17.x/api/child_process.html#child_processspawncommand-args-options), [fork](https://nodejs.org/docs/latest-v17.x/api/child_process.html#child_processforkmodulepath-args-options), and [worker_threads](https://nodejs.org/docs/latest-v17.x/api/worker_threads.html).

### Software Architecture
![basic-arch](https://user-images.githubusercontent.com/37028825/166067519-6174d01b-6d02-4d9d-a1c1-51d8fb414e00.png)

### Search Algorithms
![g124567](https://user-images.githubusercontent.com/37028825/166061379-3096c3b1-c01e-4392-b04e-a8da534eeaa3.png)



### Installers links on Drive

<https://drive.google.com/drive/folders/1BBPZhR-4YVGxHIWIV_JBFh-GS5-TREDv?usp=sharing>

### get the .deb package

<https://drive.google.com/uc?id=1Cc0GkkmN90em-FVCqWGWuJjOnih1JeeY&export=download>

### get the .rpm package

<https://drive.google.com/uc?id=1ZqsD89e1gh-VamQqFEfkqlRj_8xYwM0I&export=download>

### get the .zip package

<https://drive.google.com/uc?id=1UlRHTkF48yNpftZ2UDtuLdG28QlCh4ob&export=download>
