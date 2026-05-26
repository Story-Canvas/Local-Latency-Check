# *Simple Administration PowerShell Scripts*
## Script: Local Latency Check

**Description:**
A simple local latency checking script. Checks several websites to calculate latency average.

**Customizable:**
```powershell
param([string]$hosts = "bing.com,cnn.com,dropbox.com,github.com,google.com,ibm.com,live.com,meta.com,x.com,youtube.com")
```
- `$hosts = "websites"`: Comes with common sites already. Remove or adjust per preference.
