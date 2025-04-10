# Casa Paulista
Casa Paulista's website is built using [Zola](getzola.org).


## Getting Started
To get started with Casa Paulista, you need to have [Git](https://git-scm.com) and [Zola](https://getzola.org/) installed. You can install Zola by following the instructions on the [Zola installation page](https://getzola.org/documentation/getting-started/installation/). Git is usually pre-installed on most systems, but if you need to install it, you can find instructions in [their website](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

### Building the Site
To build the site, run the following command in the root directory of the project:

```bash
zola build
```

This will generate the static files for the site in the `public` directory.

### Running the Site Locally
To run the site locally, you can use the following command:

```bash
zola serve
```

This will start a local server and you can view the site in your web browser at `http://localhost:1111`.

### Deploying the Site
To deploy the site, you can use the following command:

```bash
git push origin main
```

This will push the changes to the `main` branch. Make sure you have set up your remote repository correctly. Also, be sure that this change does not require any review or approval from other team members. If it does, you may need to create a pull request and have it reviewed before merging it into the `main` branch.

## License
This project is licensed under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html). See the [LICENSE](LICENSE) file for more details.


