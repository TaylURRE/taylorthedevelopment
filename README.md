# Taylor the Development

This is a Next.js blog project using notion as a backend

## Creating Blog Posts

1. In Notion click new on the table to add a new row
2. Fill in the Page name, slug, Date, and Authors
3. At the top of the content area add the content you want to show as a preview (keep this under 2 paragraphs)
4. Add a divider block under your preview content
5. Add the rest of your content under the divider block

## Running Locally

To run the project locally you need to follow steps 1 and 2 of [deploying](#deploy-your-own) and then follow the below steps

1. Install dependencies `yarn`
2. Expose `NOTION_TOKEN` and `BLOG_INDEX_ID` in your environment `export NOTION_TOKEN='<your-token>'`and `export BLOG_INDEX_ID='<your-blog-index-id>'` or `set NOTION_TOKEN="<your-token>" && set BLOG_INDEX_ID="<your-blog-index-id>"` for Windows
3. Run next in development mode `yarn dev`
4. Build and run in production mode `yarn build && yarn start`

## Credits

Built using [notion-blog template](https://github.com/ijjk/notion-blog)

- Guillermo Rauch [@rauchg](https://twitter.com/rauchg) for the initial idea
- Shu Ding [@shuding\_](https://twitter.com/shuding_) for the design help
- Luis Alvarez [@luis_fades](https://twitter.com/luis_fades) for design help and bug catching
