CSS styles to _fix_ subjective styles issues in certain websites.

I'm using [Stylish][stylish-link] extension to apply these styles in Google Chrome.

---

## Fix Google Chrome links underline

**Applies to: All websites.**

```css
/*
	Disable Google Chrome links underline skipping over some characters.
*/
a:link {
    text-decoration-skip-ink: none;
}
```

| Before                           | After |
| -------------                    | -------------                    |
| ![alt text][chrome-link-before]  | ![alt text][chrome-link-after]   |


## Hide twitter statistics

**Applies to: twitter.com**

```css
/*
	Hide twitter statistics (number of tweets, folowers, following) from the twitter home page.
	Visiting a profile directly will show these stats.
*/ 

.ProfileCardStats {
	display: none;    
}

.DashboardProfileCard-userFields {
    top: 96px;
}
```

| Before                             | After                              |
| -------------                      | -------------                      |
| ![alt text][twitter-stats-before]  | ![alt text][twitter-stats-after]   |


[stylish-link]: https://chrome.google.com/webstore/detail/stylish-custom-themes-for/fjnbnpbmkenffdnngjfgmeleoegfcffe?hl=en

[chrome-link-before]: images/chrome-link-before.png "Before applying style"
[chrome-link-after]:  images/chrome-link-after.png "After applying style"
[twitter-stats-before]: images/twitter-stats-before.png "Before applying style"
[twitter-stats-after]: images/twitter-stats-after.png "After applying style"
