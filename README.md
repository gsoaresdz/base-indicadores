<h1 align="center">Python and Computer Files</h1>
<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/gsoaresdz/base-indicators?color=56BEB8">
  <img alt="Github language count" src="https://img.shields.io/github/languages/count/gsoaresdz/base-indicators?color=56BEB8">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/gsoaresdz/base-indicators?color=56BEB8">
</p>
<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0; 
  <a href="#sparkles-features">Features</a> &#xa0; | &#xa0;
  <a href="#rocket-technologies">Technologies</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requirements">Requirements</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-execution">Execution</a> &#xa0; | &#xa0;
  <a href="#memo-license">License</a> &#xa0; | &#xa0;
  <a href="https://github.com/gsoaresdz" target="_blank">Author</a>
</p>
<br>

## **:dart: About**

This project uses Python to organize store files by state into specific folders. It is ideal for those who need to manage files automatically, distributing them into folders according to their geographic location (Brazilian states).

## **:memo: Business Rule**

The Python script identifies **`.csv`** files related to different stores and distributes them into folders corresponding to each store’s state. The state is identified by the file name. For example, a file named "data_store_RJ.csv" will be moved to the folder corresponding to Rio de Janeiro (RJ).

## **:memo: Steps Executed by the Code**

1. **Creation of Folders for Each State**: Folders are created for each specified state (RJ, SP, MG, GO, AM).
2. **File Listing**: The script lists all files in the specified directory.
3. **File Distribution**: **`.csv`** files are distributed into the respective state folders based on their names.

## **:sparkles: Features**

:heavy_check_mark: **Feature 1**: Creation of folders for each specified Brazilian state.

:heavy_check_mark: **Feature 2**: Listing of all files in the specified directory.

:heavy_check_mark: **Feature 3**: Distribution of **`.csv`** files into the corresponding state folders.

## **:rocket: Technologies**

The following tools were used in this project:

- [Python](https://www.python.org/)
- [Pathlib](https://docs.python.org/3/library/pathlib.html)
- [Shutil](https://docs.python.org/3/library/shutil.html)

## **:white_check_mark: Requirements**

Before starting :checkered_flag:, you need to have [Python](https://www.python.org/) installed.

## **:checkered_flag: Execution**

### Environment Setup

This project was developed with Python 3.8. It is recommended to use this version or a more recent one to ensure compatibility.

### Library Installation

The required libraries are part of Python's standard library. Therefore, no additional libraries need to be installed.

### Running the Script

```bash
# Clone the project
$ git clone https://github.com/gsoaresdz/base-indicators.git

# Access the project directory
$ cd base-indicators

# Run the script
$ baseIndicators.ipynb
```

## **:memo: Notes**

- The script was developed for educational purposes. It can be modified to meet different needs.
- We recommend using a Python-supporting IDE, such as Visual Studio Code or PyCharm, for better support and ease of use.

## **:memo: License**

This project is under the MIT license. For more details, see the [LICENSE](LICENSE) file.

Made with :heart: by <a href="https://github.com/gsoaresdz" target="_blank">gsoaresdz</a>

<a href="#top">Back to top</a>
