# Antenati Book Downloader
This purpose of this script is to download books from the webpage Antenati. All the pages will be stored in a newly created folder, at the highest resolution possible. This way, you can look for records faster with your PC's photo application, instead of the slower webpage viewer.

Thake in mind that since all the images are on high resolution, the script will take a while to complete. A 800 page book may take up to one hour to download, and will occupy approximately 1GB of space.

To download a book, follow these instructions: 

1. Locate the IIIF manifest from the 'Contenuti collegati' section in the registry book viewer:

![IIIF manifest instruction](https://user-images.githubusercontent.com/12202169/167278949-d73cd0e0-59d4-49bb-bc4a-ba6f4db66479.jpg)

2. Right click on the link, and select 'Save link as'. Make sure you save the JSON file on the directory the jupyter notebook is located
3. Download as many manifests as you like. When you run the jupyter notebook, it will start downloading all the books.
4. All the books will be downloaded on a separate folder. Make sure to remove the JSON files once you downloaded a book, as to not download it again next time you run the script
5. You can download individual books by running the 'downloadBook' function separately.
