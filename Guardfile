# A sample Guardfile
# More info at https://github.com/guard/guard#readme

guard "jekyll-plus",
  serve: true,
  drafts: true,
  future: true,
  config_hash: {
    baseurl: ""
  } do
  watch /.*/
  ignore /^_s3.json/
  ignore /^_site/
  ignore /^bin/
  ignore /^external/
  ignore /^Gemfile(.lock)?/
  ignore /^Guardfile/
  ignore /^Readme.md/
  ignore /^License.md/
end
