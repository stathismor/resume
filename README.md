# Install

1. Install `resume-cli` as instructed here https://jsonresume.org/getting-started/
2. Install the theme by running:
    ```
    $ sudo npm install -g jsonresume-theme-stackoverflow-ibic
    ```

# Update

1. Edit `resume.json` according to [the schema](https://github.com/jsonresume/resume-schema/blob/604fb34ea13c36ba20fcff6ca86682db81ea64ee/schema.json).
2. Create an HTML version of the resume:
    ```
    $ resume export index.html --theme stackoverflow-ibic
    ```
3. Push the new `index.html` to the `gh-pages` branch
    ```
    $ git add index.html && git commit -m <comment here>
    $ git push origin gh-pages
    ```
    After a while it should be available at https://strahius.github.io/resume/
4. Create a PDF version of the resume:
    ```
    $ resume export Stathis_Moraitidis_Resume.pdf --theme stackoverflow-ibic
    ```
