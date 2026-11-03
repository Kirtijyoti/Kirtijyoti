# Profile metrics

The profile repository is private, so its README and widgets do not appear on the public profile.

## Language chart

`languages.svg` is a self-contained image based on the public GitHub language API responses saved in `language-data.json`. It uses no external image service, tokens or private repository data. Update the data and chart together when refreshing the snapshot.

## Optional view counter for a future public README

Keep this inactive while the profile README is hidden. If the profile is intentionally made public again, this optional image can be placed under the social links:

```md
![Profile views](https://komarev.com/ghpvc/?username=Kirtijyoti&style=flat-square&color=0f766e)
```

This third-party counter measures image-request page hits, not unique visitors or recruiter views. Previews and reloads can affect the value; caching and service availability can also affect it. It needs no API key. Do not add credentials to image URLs.

Sources: [counter documentation](https://github.com/antonkomarev/github-profile-views-counter), [GitHub language API](https://docs.github.com/en/rest/repos/repos#list-repository-languages).
