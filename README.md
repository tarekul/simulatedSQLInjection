# Simulated SQL Injection

### How this browser simulation was built.

Built using HTML, Javascript, and SQL.js(lightweight file-based SQL db engine that runs on browser)

### Hint to login without password or incorrect password

- username is <code>admin</code>
- use <code>--</code> to bypass password validation. In SQL <code>--</code> starts a comment and anything after it becomes a comment.
- How can we utlize the <code>--</code> to make the query string to be <code>SELECT \* FROM users WHERE username = 'admin'</code>?
- With <code>SELECT \* FROM users WHERE username = 'admin'</code> we get the result without a password
