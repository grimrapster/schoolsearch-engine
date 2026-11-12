{%- set name = get_setting('general.instance_name') -%}
# About SchoolSearch

{{name}} is a safe search engine for schools.  It gathers results from other
{{link('search engines', 'preferences')}}, flags sources that are good for
schoolwork, and blocks explicit content and games.

- **Source Check** marks results from sources that are reliable for research,
  so students can tell a good source from a weak one at a glance.
- **Safe results**: explicit content, gambling, and game sites are filtered out
  of the results.
- **No profiles**: {{name}} doesn't build a profile of the people who use it.

Send feedback or report a problem at the [{{name}} sources].

## How do I set it as the default search engine?

{{name}} supports [OpenSearch].  For more information on changing your default
search engine, see your browser's documentation:

- [Firefox]
- [Microsoft Edge] - Behind the link, you will also find some useful instructions
  for Chrome and Safari.
- [Chromium]-based browsers only add websites that the user navigates to without
  a path.

## Credits

{{name}} is built on [SearXNG], free software licensed under the [GNU AGPL-3.0].
The source code of {{name}} is available at the [{{name}} sources].


[{{name}} sources]: {{GIT_URL}}
[SearXNG]: https://github.com/searxng/searxng
[GNU AGPL-3.0]: https://www.gnu.org/licenses/agpl-3.0.html
[OpenSearch]: https://github.com/dewitt/opensearch/blob/master/opensearch-1-1-draft-6.md
[Firefox]: https://support.mozilla.org/en-US/kb/add-or-remove-search-engine-firefox
[Microsoft Edge]: https://support.microsoft.com/en-us/help/4028574/microsoft-edge-change-the-default-search-engine
[Chromium]: https://www.chromium.org/tab-to-search
