#Upgrading to the Mozu Core 9 Theme

Core 9 is the latest version of the Mozu Core theme. It was introduced with the Mozu November 2015 Service Update.

**Note:** The Base Blank theme has been deprecated. You should use the Mozu Core theme instead.

##THEME UPGRADE REQUIREMENTS

The following table shows you which features from the Mozu November 2015 Service Update require a theme upgrade. If you choose not to upgrade to a specified theme, you must manually integrate feature updates into your existing theme. The table also provides links to the Mozu Github repository where we explain what we’ve changed for these new features. Click the file diff links to see the code we updated. To review the differences between Core 8 and Core 9, view the theme comparison [here](https://github.com/Mozu/core-theme/compare/core8...master).

| FEATURE	| REQUIRED THEME | FILE DIFF |
| :-------|:---------------|:----------|
| Discount and Coupon Messaging | [Core 9](https://github.com/Mozu/core-theme) | [https://github.com/Mozu/core-theme/pull/25/files](https://github.com/Mozu/core-theme/pull/25/files) |
| Express Checkout Usability Improvements | [Core 9](https://github.com/Mozu/core-theme) | [https://github.com/Mozu/core-theme/pull/26/files](https://github.com/Mozu/core-theme/pull/26/files) |
| PayPal Express Application by Mozu	| [PayPal Express](https://github.com/Mozu/PayPalExpress-Theme) | N/A |

##HOW TO UPGRADE YOUR THEME
You can use the [Mozu Theme Generator](https://www.npmjs.com/package/generator-mozu-theme) to update a legacy theme to include changes in this version of Core. You can also run the generator in an empty directory to clone these files as the basis for a brand new theme. 

When you run the Mozu Theme Generator, the tools create a git remote to the Mozu [core-theme](https://github.com/Mozu/core-theme/tree/master) repository. In the future, you can open a terminal or command prompt and run:

`grunt mozutheme:check` 

in your local theme directory to check for updates to the Core theme.

