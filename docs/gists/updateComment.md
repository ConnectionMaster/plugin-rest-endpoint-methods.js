---
name: Update a gist comment
example: octokit.gists.updateComment({ gist_id, comment_id, body })
route: PATCH /gists/{gist_id}/comments/{comment_id}
scope: gists
type: API method
---

# Update a gist comment

```js
octokit.gists.updateComment({
  gist_id,
  comment_id,
  body,
});
```

## Parameters

<table>
  <thead>
    <tr>
      <th>name</th>
      <th>required</th>
      <th>description</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>gist_id</td><td>yes</td><td>

gist_id parameter

</td></tr>
<tr><td>comment_id</td><td>yes</td><td>

comment_id parameter

</td></tr>
<tr><td>body</td><td>yes</td><td>

The comment text.

</td></tr>
  </tbody>
</table>

See also: [GitHub Developer Guide documentation](https://docs.github.com/rest/reference/gists#update-a-gist-comment).
