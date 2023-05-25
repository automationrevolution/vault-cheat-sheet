# vault-cheat-sheet


<h2>Vault Commands Cheat Sheet</h2>
<h3>Secrets Management</h3>
<table>
<thead>
<tr>
<th>Command</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>vault kv put</code></td>
<td>Creates or updates a key-value pair in a secret backend.</td>
</tr>
<tr>
<td><code>vault kv get</code></td>
<td>Retrieves the value of a specific key in a secret backend.</td>
</tr>
<tr>
<td><code>vault kv delete</code></td>
<td>Deletes a key-value pair from a secret backend.</td>
</tr>
<tr>
<td><code>vault kv list</code></td>
<td>Lists all keys in a secret backend.</td>
</tr>
<tr>
<td><code>vault kv metadata get</code></td>
<td>Retrieves the metadata of a specific key in a secret backend.</td>
</tr>
<tr>
<td><code>vault kv metadata delete</code></td>
<td>Deletes the metadata of a specific key in a secret backend.</td>
</tr>
<tr>
<td><code>vault kv metadata list</code></td>
<td>Lists the metadata for all keys in a secret backend.</td>
</tr>
<tr>
<td><code>vault kv enable-versioning</code></td>
<td>Enables versioning for a secret backend.</td>
</tr>
<tr>
<td><code>vault kv disable-versioning</code></td>
<td>Disables versioning for a secret backend.</td>
</tr>
<tr>
<td><code>vault kv undelete</code></td>
<td>Restores a deleted key-value pair in a secret backend.</td>
</tr>
<tr>
<td><code>vault kv destroy</code></td>
<td>Permanently removes a key-value pair in a secret backend.</td>
</tr>
<tr>
<td><code>vault kv undelete-metadata</code></td>
<td>Restores a deleted key's metadata in a secret backend.</td>
</tr>
<tr>
<td><code>vault kv destroy-metadata</code></td>
<td>Permanently removes a key's metadata in a secret backend.</td>
</tr>
</tbody>
</table>
<h3>Authentication</h3>
<table>
<thead>
<tr>
<th>Command</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>vault login</code></td>
<td>Authenticates a user to Vault.</td>
</tr>
<tr>
<td><code>vault logout</code></td>
<td>Logs out the currently authenticated user.</td>
</tr>
<tr>
<td><code>vault token create</code></td>
<td>Creates a new token for authentication.</td>
</tr>
<tr>
<td><code>vault token revoke</code></td>
<td>Revokes a token, rendering it invalid.</td>
</tr>
<tr>
<td><code>vault token lookup</code></td>
<td>Retrieves information about a token.</td>
</tr>
<tr>
<td><code>vault token renew</code></td>
<td>Renews the lease of a token, extending its validity period.</td>
</tr>
<tr>
<td><code>vault token revoke-prefix</code></td>
<td>Revokes all tokens with a given prefix.</td>
</tr>
<tr>
<td><code>vault auth enable</code></td>
<td>Enables an authentication method in Vault.</td>
</tr>
<tr>
<td><code>vault auth disable</code></td>
<td>Disables an authentication method in Vault.</td>
</tr>
<tr>
<td><code>vault auth list</code></td>
<td>Lists all enabled authentication methods in Vault.</td>
</tr>
</tbody>
</table>
<h3>Policies</h3>
<table>
<thead>
<tr>
<th>Command</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>vault policy write</code></td>
<td>Creates or updates a policy with the specified name.</td>
</tr>
<tr>
<td><code>vault policy read</code></td>
<td>Retrieves the contents of a policy.</td>
</tr>
<tr>
<td><code>vault policy delete</code></td>
<td>Deletes a policy.</td>
</tr>
<tr>
<td><code>vault policy list</code></td>
<td>Lists all policies in Vault.</td>
</tr>
<tr>
<td><code>vault policy capabilities</code></td>
<td>Displays the capabilities of a policy.</td>
</tr>
<tr>
<td><code>vault write auth/token/roles/my-role</code></td>
<td>Creates or updates a token role.</td>
</tr>
<tr>
<td>`</td>
<td></td>
</tr>
</tbody>
</table>
