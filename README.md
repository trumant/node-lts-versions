# Get Node.js LTS versions

Retrieve a list of [Long Term Stable](https://nodejs.org/en/about/releases/) versions of Node.js.

Populate a GitHub Actions output `lts` with the latest LTS versions of Node

### Usage

```yaml
- name: Generate Node LTS version matrix
  uses: trumant/node-lts-versions@v1.1.1
```