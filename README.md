
## Danger Peril Settings

### What is this project?

This is the configuration repo for Peril on the ReSwift org. There is a [settings file](peril.settings.json) and org-wide dangerfiles which are inside the [org folder](org).

Here's some links to the key things

* [Peril](https://github.com/danger/peril)
* [Danger JS](http://danger.systems/js/)
* [Peril for Orgs](https://github.com/danger/peril/blob/master/docs/setup_for_org.md)
* [Peril on the Danger Heroku team](https://dashboard.heroku.com/apps/peril-danger-staging)

### To Develop

```sh
git clone https://github.com/ReSwift/reswift-peril.git
cd reswift-peril
yarn install
code .
```

You will need node and yarn installed beforehand. You can get them both by running `brew install yarn`. This will give you auto-completion and types for Danger/Peril mainly.

