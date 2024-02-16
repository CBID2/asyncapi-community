---
title: SEO
description: This guide gives advice on how to implement SEO when creating tutorials for our project.
---

## What is SEO?

SEO (Search Engine Optimization) refers to the methods and strategies used to enhance the visibility of a website's content in search engine results.

### Why is important in our Documentation?

Implementing SEO practices would make it easier for our users and others to find them, resulting in more contributions and people to our community.  

### SEO Best Practices  

#### Headings

Headings are tags used to make sub titles distinctive from each other. When it comes to making them SEO-friendly, it's highly recommended to do the following:

- **Put them in hierarchcial order:** Since an `h1` tag tend to be titles, always start with this tag. From there, use `h2` and`h3` tags for the subsections and `h4` and `h5` tags for other sections in your tutorial or other piece of documentation.
- **Be descriptive:** Avoid using terms like "Conclusion" and "Introduction" due to their vagueness. Instead, make them specific and ensure they describe the section's content.
- **Include keywords:** Since sites like Google often use keywords to help people's online content appear on the web, Adding these terms effectively is helpful in reaching the tutorials or other pieces of content you create for our project to a wider audience.

Here's an example of SEO-friendly headings:

```md
# Server 
## What is Server?
## What is the purpose of servers?
### Cilent and Server
```

#### Alt Text

Alt text are short descriptions of images used to help Google and people who use screen readers gain a better understanding of our tutorials and other pieces of content. To make them SEO-friendly, it's highly recommended to do the following:

- **Describe the image accurately**:  Doing this would help our users understand how to use Asycapi in their work.
- **Be concise**: While accuracy is important, avoid writing every single detail about the image.
- **Use keywords strategically**: Avoid adding every single keyword to your image's alt text. It can overwhelm Google's search engine.

Here's an example of effective alternative text:

```html
alt="Diagram of EDAs"
```

#### URLs

URLs are addresses to webpages and other forms of online content. In the context of SEO, they help make it easier for users to gain access content. To make them more SEO-friendly, use the following methods:

- **Make them short:** It'll make the links easier for users to comprehend and find the needed tutorial on our website
- **Use keywords**: Like alt text, effectively adding keywords in the URL would make it easier for Google to find them.
- **Avoid using special characters and spaces:** Use hyphens (-) instead of underscores (_) to separate words in URLs, as search engines treat hyphens as space.

Here are some examples of SEO-friendly URLs from our documentation:
- `https://www.asyncapi.com/docs/concepts/application`
- `https://www.asyncapi.com/docs/concepts/server`
- `https://www.asyncapi.com/docs/concepts/message`

#### Additional Suggestions
- **Meta Descriptions:** Our current docs and blog posts all use meta descriptions and titles. These summaries appear under the title in search results and can significantly impact click-through rates.
- **Mobile-Friendliness:** Mention the importance of ensuring that documentation is mobile-friendly, as this is a factor in search engine rankings.
- **Internal Linking:** Encourage the use of internal linking to other parts of the documentation or the AsyncAPI website to boost SEO and user navigation.
- **Content Quality:** Emphasize the importance of high-quality, original content. Search engines favor content that provides value to users.
  **Anchor Text:**
- Be descriptive and relevant.
- Avoid generic phrases like "click here" or "this page". (Instead, use meaningful phrases that give users and search engines an idea of what to expect on the linked page.)
- Vary your anchor text. While it's important to be descriptive, using the exact same anchor text for every link to a particular page can appear spammy to search engines. Try to vary the phrasing while still being clear about the page content.