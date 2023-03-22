# nextでgtmを使用する際の最低限のテンプレート
### 注意点
- scriptタグはnextが用意しているScriptコンポーネントではなく純粋なhtmlの<script>でなければ反応しない
### 使用方法
- GTMから発行されたキーを .env.localに以下のように書く
  ``` 
  NEXT_PUBLIC_GOOGLE_TAG_MANAGER_ID = [yourKey]
  ```
  
以上。
