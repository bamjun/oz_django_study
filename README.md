[강의자료](https://brass-alder-325.notion.site/Django-ca81d4798d0a4bb7a0f038956dafda8d)



- `&&` 직렬실행, `&` 병렬실행.  
  &darr; `/` &darr; `bash shell`
  ```bash
  poetry run isort . && poetry run black . && poetry run mypy .
  ```

  poetry add pymysql cryptography