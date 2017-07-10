
#### 如何把issues 滙出成 CSV 檔案

##### 參考作法一： stackoverflow [How can I export GitHub issues to Excel?](https://stackoverflow.com/questions/41369365/how-can-i-export-github-issues-to-excel)
1. Just open the following URL in a browser substituting the {owner} and {repo} with real values:

    https://api.github.com/repos/{owner}/{repo}/issues?page=1&per_page=100

    // json format
    
2. Convert JSON to CSV : https://konklone.io/json/

##### 參考作法二： python [Exporting github issues to csv](https://stackoverflow.com/questions/30133615/exporting-github-issues-to-csv)


