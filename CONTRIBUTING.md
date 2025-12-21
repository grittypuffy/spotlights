# Contributing

## First-time contributors

### Guidelines

- You must have made a pull request that has been merged in our repositories.
- The pull request adds a feature, improves documentation or fixes a bug. Typo fixes will not be considered.

### Submit your blog

1. Fork this repository
2. Clone the forked repository
    ``` sh
    git clone https://github.com/<your-username>/spotlights # Use your fork name if you named it differently
    cd spotlights
    ```
3. Copy the contributor blog template from `templates/contributor.md` to `content/spotlight/contributor/<yyyy>/<mm>` where `yyyy` and `mm` are the year and month in which you are submitting the pull request with the blog in this repository.

    Name the filename as `<author>--<title>.md` where `author` is your name and `title` is the title of your blog.

    For example, if your name is "John Doe" and your blog title is "Making my first contribution to TranscribeIt: A beginner's journey", the file name will be `john-doe--making-my-first-contribution-to-transcribeit-a-beginners-journey.md`
    
    Avoid special characters other than hyphens (-) and avoid capital letters for file name.
    
    ``` sh
    cp templates/contributor.md content/spotlight/contributor/<yyyy>/<mm>/<author>--<title>.md
    ```
4. Fill the blog details using Markdown. For using Markdown, you can check out https://www.tomarkdown.org/guides/markdown-tutorial-for-beginners. Avoid using images, slang, gendered pronouns or language (guys, bros, etc. For more information, check out https://heyguys.cc) or language that violates our [code of conduct](https://fossia.org/resources/code-of-conduct). If you are stuck with writing your blog, feel free use LLMs and/or reach out on our Matrix general room for queries, we will be happy to help.
5. Commit and submit the changes as a pull request to our repository.

Congratulations, we are happy for you for making your first contribution! We will review the content and add your blog!

## Mentors

### Guidelines

- You must have reviewed code under our repositories
- The pull request that's reviewed must be merged
- The pull request was made by a beginner or new contributor
- You have been an active mentor for more than a month

### Submit your blog

1. Fork this repository
2. Clone the forked repository
    ``` sh
    git clone https://github.com/<your-username>/spotlights # Use your fork name if you named it differently
    cd spotlights
    ```
3. Copy the mentor blog template from `templates/mentor.md` to `content/spotlight/mentor/<yyyy>/<mm>` where `yyyy` and `mm` are the year and month in which you are submitting the pull request with the blog in this repository.

    Name the filename as `<author>--<title>.md` where `author` is your name and `title` is the title of your blog.

    For example, if your name is "John Doe" and your blog title is "On mentoring first-time contributors", the file name will be `john-doe--on-mentoring-first-time-contributors.md` 

    Avoid special characters other than hyphens (-) and avoid capital letters for file name.
    
    ``` sh
    cp templates/mentor.md content/spotlight/mentor/<yyyy>/<mm>/<author>--<title>.md
    ```
4. Fill the blog details using Markdown. For using Markdown, you can check out https://www.tomarkdown.org/guides/markdown-tutorial-for-beginners. Avoid using images, slang, gendered pronouns or language (guys, bros, etc. For more information, check out https://heyguys.cc) or language that violates our [code of conduct](https://fossia.org/resources/code-of-conduct). If you are stuck with writing your blog, feel free use LLMs and/or reach out on our Matrix general room for queries, we will be happy to help.
5. Commit and submit the changes as a pull request to our repository.

Thank you so much for mentoring and making free and open source contributions less daunting for all!
