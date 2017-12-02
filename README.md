# Introducion
The need and importance of extracting data from the web is becoming increasingly loud and clear. Every few weeks, I find myself in a situation where we need to extract data from the web. For example, last week we were thinking of creating an index of hotness and sentiment about various data science courses available on the internet. This would not only require finding out new courses, but also scrape the web for their reviews and then summarizing them in a few metrics! This is one of the problems / products, whose efficacy depends more on web scrapping and information extraction (data collection) than the techniques used to summarize the data.

# Scraping
Web scraping is a computer software technique of extracting information from websites. This technique mostly focuses on the transformation of unstructured data (HTML format) on the web into structured data (database or spreadsheet).
You can perform web scrapping in various ways, including use of Google Docs to almost every programming language. I would resort to Python because of its ease and rich eocsystem. It has a library known as ‘BeautifulSoup’ which assists this task. In this article, I’ll show you the easiest way to learn web scraping using python programming.

## BeautifulSoup
 It is an incredible tool for pulling out information from a webpage. You can use it to extract tables, lists, paragraph and you can also put filters to extract information from web pages. In this article, we will use latest version BeautifulSoup 4.
 
 # Basics – Get familiar with HTML (Tags)
 While performing web scarping, we deal with html tags. Thus, we must have good understanding of them.  Below is the basic syntax of HTML:HTMLThis syntax has various tags as elaborated below:

![html](https://user-images.githubusercontent.com/23000971/33509613-1dc5768a-d729-11e7-8e13-4d8845566bd0.png)

![capture](https://user-images.githubusercontent.com/23000971/33509704-e6399e52-d729-11e7-9347-749a6401d477.JPG)

## Other useful HTML tags are:

HTML links are defined with the <a> tag, “<a href=“http://www.test.com”>This is a link for test.com</a>”
HTML tables are defined with<Table>, row as <tr> and rows are divided into data as <td>
HTML list starts with <ul> (unordered) and <ol> (ordered). Each item of list starts with <li>

![table](https://user-images.githubusercontent.com/23000971/33509615-1df17280-d729-11e7-9876-5c3c75c7285d.png)
