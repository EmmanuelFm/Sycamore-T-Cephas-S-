| 키               | 유형    | 설명                                                                                                                                                                                            |
| --------------- | ----- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `ref`           | `문자열` | The [`git ref`](/rest/reference/git#get-a-reference) resource.                                                                                                                                |
| `ref_type`      | `문자열` | The type of Git ref object created in the repository. Can be either `branch` or `tag`.                                                                                                        |
| `master_branch` | `문자열` | The name of the repository's default branch (usually {% if currentVersion == "free-pro-team@latest" or currentVersion ver_gt "enterprise-server@2.23" %}`main`{% else %}`master`{% endif %}). |
| `설명`            | `문자열` | The repository's current description.                                                                                                                                                         |