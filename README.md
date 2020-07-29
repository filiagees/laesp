# laesp

## error exporting as SVG
The full issue where this tests were used [is here](https://github.com/plotly/Kaleido/issues/23).

### steps to reproduce
* install and load venv
* run the script `test_generate_svg.ipynb`

Other options is directly run the file `run_kaleido.sh` (it has hardcoded paths, considering this repo was cloned in `/_/git/laesp/`)

If you simulated properly, you will get the error:
```
[0726/203448.792822:WARNING:resource_bundle.cc(435)] locale_file_path.empty() for locale 
[0726/203448.810668:WARNING:resource_bundle.cc(435)] locale_file_path.empty() for locale 
[0726/203448.810920:WARNING:resource_bundle.cc(435)] locale_file_path.empty() for locale 
{"code": 0, "message": "Success", "result": null, "version": "0.0.2"}
[0726/203448.835198:WARNING:resource_bundle.cc(435)] locale_file_path.empty() for locale 
{"code":525,"message":"Unexpected error while fetching from test/sample.json","pdfBgColor":null,"format":"svg","result":null,"width":700,"height":500,"scale":1}
```
