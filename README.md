# Urbantech website

This is a simple website done with [Bulma](https://bulma.io/)

## Prerequisites

1. To work efficiently on code, an editor is required. Many engineers use the open source editor [VSCode](https://code.visualstudio.com/)

2. We manage our software using Git, which is a version control system. We use Github as the platform to manage our repositories, team and projects. Git is one of our most basic tools. You can learn all you need [here in Github guides](https://guides.github.com/)

## Contributing

The first step is to find an interesting Issue from the [current project](https://github.com/map-of-solidarity/geo-bel-map-of-solidarity/projects/1).

Assign the Issue to yourself.

Clone the repo to your local machine.

Create a new branch with the format `<issue number>-basic_description` e.g. `3-products-secgtion`

### Running locally

It is recommended to use a local web server like [HTTP Server](https://github.com/http-party/http-server)

1. Install [Node Version Manager](https://github.com/nvm-sh/nvm#install--update-script)
2. Install Node.js and NPM

    ```shell
    nvm install node
    ```

3. Install http-server

    ```shell
    npm i -g http-server
    ```

4. Start the http server in the root directory for this project

    ```shell
    http-server
    ```

5. Access the website in your browser [http://localhost:3000](http://localhost:3000)

### Making changes

The source files can be modified directly – the website is defined in the `index.html` file.
Using the editor, modify the file `index.html` and other files as needed.

Refresh the page in your browser. You should see the changes.

### Creating commits

When you are done, commit your work. We use the message format `changes description #<issue_number>`.

Publish to Github (subsitute `<branch_name>` for e.g. `3-products-secgtion`):

```shell
git push -u origin <branch_name>
```

Create a PR via Github. Await your PR to be reviewed. Once it passes review, it will be merged to `master`.
