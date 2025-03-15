# Dance class viewer

Here's a nice way to do the project. I think the first step is to do things kind of manually. This means just build the webscraper, save the output in a json or csv locally, and use it to render the site. Then you can automate this process by running all of these things automatically in a GitHub action, Firebase function, or maybe you can just do it in Streamlit. Here are some specific tools I recommend:
- [Streamlit](https://streamlit.io/) for frontend, deployment, and hosting.
- Webscraping: [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) for simple sites that just need html extraction and [Selenium](https://www.selenium.dev/) or [Playwright](https://playwright.dev/) for more complex stuff.

Here are some alternatives you can try:
- [NiceGUI](https://nicegui.io/) for frontent in Python.
- [React](https://react.dev/) for frontend.
