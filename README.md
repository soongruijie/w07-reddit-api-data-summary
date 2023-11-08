# LSE DS105A (2023/24) - Week 07: Data summarisation and the grammar of graphics

<figure>
    <img src="./figures/DS105L_favicon.png" alt="Image Created with Stable Diffusion"  role="presentation" style="object-fit: cover;width:5em;height:5em;border-radius: 50%;">
    <figcaption>
        <span style="display:inline-block;font-size:0.3em;width:30%;">
        </span>
    </figcaption>

</figure>
<br/>
<br/>

This simple repository contains code and data used in Week 07 of 2023's edition of [DS105A](https://lse-dsi.github.io/DS105/).


# 📚 PREPARATION

If you want to replicate the analysis in this notebook, you will need to:

1. Clone this repository to your computer
2. Add it to your VS Code workspace
3. Create a [Reddit account](https://www.reddit.com/register/)
4. Then, follow these [First Steps](https://github.com/reddit-archive/reddit/wiki/OAuth2-Quick-Start-Example#first-steps) to create an app and get your credentials.
5. Take note of your Reddit username and password, as well as the client ID and client secret of the app you created:

    ![](./figures/screenshot_reddit_app_details.png)

6. Create a plain text file called `credentials.json` and add your Reddit credentials there:

    ```json
    {
        "reddit_username": "<your Reddit username>",
        "reddit_password": "<your Reddit password>",
        "app_client_id": "<your Reddit app's client ID>",
        "app_client_secret": "<your Reddit app's client secret>"
    }
    ```

7. Install the required packages (see below)

    ```bash
    pip install "tqdm==4.65.0" "pandas>=2.1" "plotnine>0.12" "altair>=5" "pyaml>=6.0.1" "matplotlib>=3.7"
    ```

    Or, better yet, use the `requirements.txt` file provided in this repository:

    ```bash
    pip install -r requirements.txt
    ```


**🖇️ USEFUL LINKS:**

- W3 Schools' [HTTP Request Methods](https://www.w3schools.com/tags/ref_httpmethods.asp) page
- Reddit API's [documentation](https://www.reddit.com/dev/api)
- The [JSON Crack Extension](https://marketplace.visualstudio.com/items?itemName=AykutSarac.jsoncrack-vscode) for VS Code or [the website version](https://jsoncrack.com/)
- 🐼 pandas' [`pd.json_normalize()` function documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.json_normalize.html)
