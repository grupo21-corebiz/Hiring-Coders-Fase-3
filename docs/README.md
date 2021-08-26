# Minimum Boilerplate Theme

The minimum Boilerplate Theme is basic store front model based on the VTEX IO Store Framework.

It should be used only when you want to start a new store theme without any pre-set configurations, as is the case with [Store Theme](https://github.com/vtex-apps/store-theme). 

While Store Theme gives developers a ready-to-go default store front structure, the Minimum Boilerplate Theme will enable you to build you store freely from scratch.

## Configuration

### Step 1 -  Basic setup

Access the VTEX IO [basic setup guide](https://vtex.io/docs/getting-started/build-stores-with-store-framework/1) and follow all the given steps. 

By the end of the setup, you should have the VTEX command line interface (Toolbelt) installed along with a developer workspace you can work in.

### Step 2 - Cloning the Minimum Boilerplate Theme repository

[Clone](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) this repository to your local files to be able to effectively start working on it.

Then, access the repository's directory using your terminal. 

### Step 3 - Editing the `Manifest.json`

Once in the repository directory, it is time to edit the Minimum Boilerplate `manifest.json` file. 

Once you are in the file, you must replace the `vendor` and `account` values. `vendor` is the account name you are working on and `account` is anything you want to name your theme. For example:

```json
{
  "vendor": "storecomponents",
  "name": "my-test-theme",
}
```

### Step 4 -  Installing required apps

In order to use Store Framework and work on your store theme, it is needed to have both `vtex.store-sitemap` and `vtex.store` installed.

Run  `vtex list`  and check whether those apps are already installed. 

If they aren't, run the following command to install them: `vtex install vtex.store-sitemap vtex.store -f`

### Step 5 -  Uninstalling any existing theme

By running `vtex list`,  you can verify if any theme is installed.

It is common to already have a `vtex.store-theme`  installed when you start the store's front development process. 

Therefore, if you find it in the app's list, copy its name and use it together with the command `vtex uninstall`. For example:

```json
vtex uninstall vtex.store-theme
```

### Step 6- Run and preview your store

Then time has come to upload all the changes you made in your local files to the platform. For that, use the `vtex link` command. 

If the process runs without any errors, the following message will be displayed: `App linked successfully`. Then, run the `vtex browse` command to open a browser window having your linked store in it.

This will enable you to see the applied changes in real time, through the account and workspace in which you are working.

### Paleta de cores:

- background: #000000 ![#000000](https://via.placeholder.com/15/000000/000000?text=+)

- big_text: #ffffff ![#ffffff](https://via.placeholder.com/15/ffffff/000000?text=+)

- title1: #f1c233 ![#f1c233](https://via.placeholder.com/15/f1c233/000000?text=+)

- title2: #000000 ![#000000](https://via.placeholder.com/15/000000/000000?text=+)

- subtitle: #666666 ![#666666](https://via.placeholder.com/15/666666/000000?text=+)

- Button: #2680EB ![#2680EB](https://via.placeholder.com/15/2680EB/000000?text=+)

- ButtonOnMouseOver: #2870C6 ![#2870C6](https://via.placeholder.com/15/2870C6/000000?text=+)

- Button_font: #ffffff ![#ffffff](https://via.placeholder.com/15/ffffff/000000?text=+)

- Framework1: #F1C233 ![#F1C233](https://via.placeholder.com/15/F1C233/000000?text=+)

- Framework2: #2680EB ![#2680EB](https://via.placeholder.com/15/2680EB/000000?text=+)

- Framework3: #953764 ![#953764](https://via.placeholder.com/15/953764/000000?text=+)

- Framework4: #CE7C3E ![#CE7C3E](https://via.placeholder.com/15/CE7C3E/000000?text=+)

- grayScale1: #434343 ![#434343](https://via.placeholder.com/15/434343/000000?text=+)

- grayScale2: #666666 ![#666666](https://via.placeholder.com/15/666666/000000?text=+)

- grayScale3:#999999 ![#999999](https://via.placeholder.com/15/999999/000000?text=+)

- grayScale4: #B7B7B7 ![#B7B7B7](https://via.placeholder.com/15/B7B7B7/000000?text=+)

- MediaSlide1background: #FF6E60 ![#FF6E60](https://via.placeholder.com/15/FF6E60/000000?text=+)

- MediaSlide2background: #91A7D0 ![#91A7D0](https://via.placeholder.com/15/91A7D0/000000?text=+)

- ContactAreaBackgroung: #F5F5F5 ![#F5F5F5](https://via.placeholder.com/15/F5F5F5/000000?text=+)

- ContactAreaPlaceHolderfontcolor: #D0D0D0 ![#D0D0D0](https://via.placeholder.com/15/D0D0D0/000000?text=+)

- formFontColor: #000000 ![#000000](https://via.placeholder.com/15/000000/000000?text=+)

- ContactAreaButton: #D0D0D0 ![#D0D0D0](https://via.placeholder.com/15/D0D0D0/000000?text=+)

- ContactAreaButtonActive: #000000 ![#000000](https://via.placeholder.com/15/000000/000000?text=+)
