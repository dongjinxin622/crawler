# news crawler

The main file includes functions for collecting data from websites.

The Excel file outlines key elements for each institution's news page:
    Institution: Name of the organization (e.g., ISED, NIST, NSF).
    URL: Base link to the news section of the website.
    HTML Elements for News Extraction:
    news_name: HTML tag/container for individual news items (e.g., article, div).
    news_class: CSS class of the news container (e.g., item, latest-news-teaser).
    title_name/tag: Tag for the news title (e.g., a, span).
    title_class: Class of the title element (e.g., entry-title).
    link_name/tag: Tag for the news link (e.g., a).
    link_class: Class of the link element (e.g., href).
    time_name/tag: Tag for the publication date (e.g., time, p).
    time_class: Class of the date element (e.g., post-summary__date).
    source_link: Base URL for constructing absolute links (if needed).

