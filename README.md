# LinkedIn Resume Generator

Create your resume site in a matter of seconds by using your LinkedIn profile data.

**Some benefits:**

- It is the fastest web to create your resume site
- Stop wasting so much time updating your site after you update your LinkedIn
- Many templates to choose from
- It is completely free!

## How to use

### Basic usage

1. Save your LinkedIn profile data
2. Run a simple command:

```shell
npx linkedin-resume-generator --input ~/downloads/my-resume.html --output ~/my-output-dir --template your-template
```

3. Open the `index.html` on your output directory with your browser and see the result for yourself
4. Host it wherever you want

### Clean cache

Every time a template it used, it's repository is cached at. If you want to clean that cache, for example, to get a template update, just run:

```shell
npx -p linkedin-resume-generator clean
```

## How to save your LinkedIn profile data

TODO

## Extra configuration

TODO

## FAQ

**There is a weird error that I don't understand**

Try adding the flag `--debug` and see if that helps you understand, if not, please refer to our [Github issues](https://github.com/resume-site-builder/linkedin-resume-generator/issues)
