# hexo-theme-next-blog

<!-- ATTENTION!
1. Please, write pull request readme in English. Not all contributors / collaborators know Chinese and Google translate can't always translate issues accurately. Thanks!

2. Always remember that NexT includes 4 schemes. And if on one of them works fine after the changes, on another scheme this changes can be broken. Muse and Mist have similar structure, but Pisces is very difference from them. Gemini is a mirror of Pisces with some styles and layouts remakes. So, please, make the tests at least on two schemes (Muse or Mist and Pisces or Gemini).
-->

## PR Checklist
**Please check if your PR fulfills the following requirements:**
<!-- Change [ ] to [X] to select -->

- [X] The commit message follows [our guidelines](https://github.com/theme-next/hexo-theme-next/blob/master/.github/CONTRIBUTING.md).
- [X] Tests for the changes was maked (for bug fixes / features).
   - [X] Muse | Mist have been tested.
   - [X] Pisces | Gemini have been tested.
- [X] Docs in [NexT website](https://theme-next.org/docs/) have been added / updated (for new features).

## PR Type
**What kind of change does this PR introduce?**

- [ ] Bugfix.
- [X] Feature.
- [ ] Code style update (formatting, local variables).
- [ ] Refactoring (no functional changes, no api changes).
- [ ] Build related changes.
- [ ] CI related changes.
- [ ] Documentation content changes.
- [ ] Other... Please describe:

## What is the current behavior?
<!-- Please describe the current behavior that you are modifying, or link to a relevant issue. -->
Add an end tag at the end of the post

Issue resolved: N/A

## What is the new behavior?
<!-- Description about this pull, in several words... -->
Add an end tag at the end of the post

- Screenshots with this changes: N/A
- Link to demo site with this changes: N/A

### How to use?
In NexT `_config.yml`:
```yml
post_end_tag:
  enabled: true
  message: Thanks for reading
```

## Does this PR introduce a breaking change?
- [ ] Yes.
- [X] No.
