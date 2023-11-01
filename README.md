# CAD_Phase wise project submission
GitHub link:
# Set Up Your Blog: 
Before you deploy your blog, you should have your blog content ready in the form of HTML, CSS, and JavaScript files. You can create your blog using static site generators like Jekyll, Hugo, or frameworks like React or Vue.js.

# Create an IBM Cloud Account:

If you don't already have an IBM Cloud account, sign up for one at IBM Cloud.
Log in to your IBM Cloud account.
# Create a Static Web App:

In IBM Cloud, you can use the IBM Cloud Static Web Apps service to deploy your blog. The steps may vary depending on the updated user interface, but generally, you should be able to find a way to create a new Static Web App.
# Configure Your Web App:

Configure your Static Web App with the settings required for your blog. You'll need to specify the repository or source for your blog files, set up build and deployment configurations, and define any environment variables.
# Build and Deploy Your Blog:

Depending on your configuration, the IBM Cloud Static Web Apps service should automatically build and deploy your blog from your source code repository. It may use a build script like npm run build for JavaScript-based projects.
# Custom Domain (Optional):

If you have a custom domain for your blog, configure it to point to your deployed IBM Cloud Static Web App. This involves setting up DNS records to direct traffic to your blog.
# Testing:

Verify that your blog is live by visiting the provided URL. Ensure that all pages and content are rendering correctly.
# Content Updates:

As you make updates to your blog, push the changes to your source code repository. Depending on your configuration, the IBM Cloud Static Web Apps service should automatically rebuild and deploy the updates.
# Personal Blog on IBM Cloud Static Web Apps

Welcome to your personal blog hosted on IBM Cloud Static Web Apps. This README will guide you through the website's navigation, updating content, and managing dependencies.

## Website Navigation

### Homepage
The homepage is the landing page of your blog. Visitors can see the latest blog posts, featured articles, or any introductory content you choose to display here.

### Blog Posts
All your blog posts can be accessed through the "Blog" section in the website's navigation menu. Visitors can browse, search, and read your articles. Each blog post typically includes a title, content, and any associated media.

### Categories and Tags
To make it easier for visitors to find specific content, you can categorize and tag your blog posts. Create categories and add tags to your posts to help organize your content. Visitors can filter articles based on these categories and tags.

### About Me
You may want to include an "About Me" page that provides information about yourself, your background, and your interests. This personal touch helps readers connect with the author.

### Contact
Include a "Contact" page that allows visitors to get in touch with you. You can provide a contact form, email address, or social media links for communication.

## Updating Content

### Blog Post Creation
1. # Create a New Blog Post:
2. To add a new blog post, follow these steps:
   - Create a new Markdown file for your blog post. Make sure to name it with a meaningful and SEO-friendly title, like my-new-blog-post.md.
   - Add the content of your blog post using Markdown syntax. Include metadata like the title, date, and any tags or categories.
   - Save the Markdown file in the designated directory for your blog posts.

3. # Images and Media:
4. If your blog post includes images or other media files, save them in the appropriate directory and reference them in your Markdown file.

5. # Front Matter:
6. Make sure to include front matter (metadata) at the beginning of your Markdown file. Here's an example:
   markdown
   ---
   title: My New Blog Post
   date: 2023-11-01
   tags: [technology, web development]
   categories: [programming]
   ---
   

### Content Updates
1. To make updates to existing blog posts, locate the corresponding Markdown file in the blog post directory and edit it.

2. If you want to update the homepage or other non-blog content, access the corresponding HTML or Markdown files and modify the content as needed.

### Deployment
Your content updates are automatically deployed to the website when you push changes to your source code repository. No additional steps are required for deployment.

## Dependencies

This personal blog is built on a static website generator or framework, and it may have specific dependencies. Please refer to the documentation of your chosen website generator or framework for details on managing dependencies, themes, and customizations.

- If you are using a JavaScript-based framework (e.g., React, Vue), you might have dependencies managed through npm or yarn. Use the respective package manager to install or update these dependencies.

- If you are using a static site generator (e.g., Jekyll, Hugo), ensure that you have the required dependencies and plugins installed. Refer to the official documentation for guidance.

## Feedback and Assistance

If you encounter any issues, have questions, or need assistance with your personal blog, please reach out to the support team or the community of the website generator or framework you are using. They can provide guidance and solutions for specific technical issues.

Thank you for using IBM Cloud Static Web Apps to host your personal blog. Happy blogging!
