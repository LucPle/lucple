name: Example (pdf output)
uses: lowlighter/metrics@latest
with:
  template: markdown
  filename: metrics.markdown.pdf
  markdown: >-
    https://raw.githubusercontent.com/lowlighter/metrics/master/source/templates/markdown/example.pdf.md
  config_output: markdown-pdf
  plugin_rss: yes
  plugin_rss_source: https://news.ycombinator.com/rss
  plugin_rss_limit: 4
  plugin_isocalendar: yes
  config_twemoji: yes
  config_padding: 5%
  token: ${{ secrets.METRICS_TOKEN }}
