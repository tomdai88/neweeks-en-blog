title: "{{ replace .File.ContentBaseName "-" " " | title }}" # Article title, automatically generated from filename
date: {{ .Date }} # Article creation date, automatically filled
lastmod: {{ .Date }} # Last modified date, can be same as date or manually updated later
draft: true # Set to true for draft, false to publish. Default is draft when created.

description: "This is a brief description of the article for lists or search results. Control the summary content here." # Article summary/description

Optional Front Matter fields for SEO and categorization. Uncomment and fill as needed.
categories:
- "Uncategorized" # Example category, modify as needed
tags:
- "New Article" # Example tag, modify as needed
keywords: "keyword1, keyword2, keyword3" # Optional keywords, comma-separated
Featured image for the blog list page. Path is relative to the page bundle folder.
image: "featured.jpg"
Whether to display the image on the single post page (depends on theme support)
showImage: true
Other custom fields (optional)
author: "Your Name"
series: "Your Series Name"
Welcome to my new article: {{ replace .File.ContentBaseName "-" " " | title }}
Start your article content here.

In the provided Markdown file content, the following Front Matter sections are crucial for SEO optimization as they should highly match the main content (body of the article):

title (Front Matter): The article's title.

description (Front Matter): The article's meta description.

tags (Front Matter): The tags associated with the article.

categories (Front Matter): The categories the article belongs to.

keywords (Front Matter) (Optional): Specific keywords for the article.

Why these parts matching the main content is crucial for SEO:

Title: The title is one of the most important factors for search engines to determine the page's topic and content relevance. If the title does not match the article content, search engines may consider the page content to be of low quality or misleading to users, thus affecting rankings. The title also appears directly in search results, attracting user clicks, so it needs to accurately summarize the core content of the article and include relevant keywords.

Description: While the description does not directly influence ranking algorithms, it serves as a summary in search results and greatly impacts the user's click-through rate (CTR). An accurate and keyword-rich description can attract users and increase CTR. If the description does not match the actual content, user experience will degrade, leading to a high bounce rate, indirectly affecting rankings.

Tags and Categories: These metadata help search engines understand the article's topic and domain. They provide more contextual information for the content, enabling search engines to better match the article with relevant search queries. Additionally, these taxonomy pages themselves can be indexed, providing user navigation and further enhancing the site's structure and user experience.

Keywords: Although modern SEO no longer relies on keyword lists as heavily as in the past, they can still serve as supplementary information to help you and search engines confirm the article's core topics. Most importantly, these keywords should be naturally integrated into the article's title, description, and body content. If the keywords list is completely unrelated to the actual content, they lose their meaning and may even be considered keyword stuffing.

The core idea is "relevance and consistency":
Search engines aim to provide users with the most relevant and useful information. If your title, description, tags, and keywords clearly indicate the article's topic, and these topics are explored in depth and with high quality in the body of the article, then search engines will find it easier to understand your content and present it to the appropriate search users, thereby improving your SEO ranking.

Therefore, all the aforementioned Front Matter fields should highly summarize and accurately reflect the core topics and keywords discussed in the article's main body.

You can add paragraphs, lists, code blocks, and other Markdown elements here.

Subheading Example
This is content under a subheading.

{{< figure src="my-image.jpg" caption="An example image in the page bundle." >}}

Hope you enjoy writing!