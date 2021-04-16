{% data variables.product.prodname_code_scanning_capc %} is a feature that you use to analyze the code in a {% data variables.product.prodname_dotcom %} repository to find security vulnerabilities and coding errors. Any problems identified by the analysis are shown in {% if currentVersion ver_gt "enterprise-server@2.21" or currentVersion == "github-ae@latest" %}{% data variables.product.prodname_ghe_server %}{% else %}{% data variables.product.prodname_dotcom %}{% endif %}.