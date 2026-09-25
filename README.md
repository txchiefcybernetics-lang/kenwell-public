🚀 AUTOMATED BUILD & DEPLOYMENT CENTER
# Kenwell Publisher — Team  KENWELL AI AGENT TERMINAL (Ollama)


A small repository containing an exported HTML file (kenwell-publisher.htm) that appears to represent a "Team / Name" or publisher page exported from a Windows Downloads folder. This README explains what the repository contains, how to view the file, and suggested next steps.

## Contents
- kenwell-publisher.htm — An HTML file (exported/saved copy) that likely contains team information or a publisher page.
- README.md — This file.

## Purpose
This repository stores a snapshot of the exported HTML file so it can be preserved, reviewed, and (optionally) improved or integrated into a website. It is useful when you want to:
- Keep a versioned copy of the exported page.
- Share the file with collaborators.
- Edit and convert the page into a more structured site or component.

## How to view
To view the HTML locally:
1. Download/clone the repository.
2. Open `kenwell-publisher.htm` directly in your web browser (double-click or use File → Open).http://clientportal.duckdns.org/
   - Some features that rely on local resources or scripts may not work when opened via `file://`.
3. To serve it over HTTP (recommended), run a simple local server from the repository root:
   - Python 3: `python -m http.server 8000` then open `http://localhost:8000/kenwell-publisher.htm`
   - Node (http-server): `npx http-server -p 8000` then open `http://localhost:8000/kenwell-publisher.html`

## Suggested next steps
- Inspect the HTML for sensitive or personal data before publishing.
- If this file is a single-page export, consider:
  - Breaking content into template(s) (HTML/CSS/JS) for reuse.
  - Converting into a Markdown-based page and adding to a static site generator (Jekyll, Hugo, etc.).
  - Cleaning up inline styles/scripts and moving them into separate files for maintainability.
- Rename the repository to a clearer project name if this is intended to be a project rather than a single-file backup.

## Contributing
If you want to collaborate:
- Open an issue describing what you'd like to change (e.g., clean markup, responsive styles, accessibility fixes).
- Create a branch, make your edits, and submit a pull request with a short description of changes.

## License
No license is included. If you want others to reuse or contribute, add a LICENSE file (for example MIT or Apache-2.0).

## Contact / Maintainer
Repository owner: KENWELL-TX-ORG (as listed in the repository URL).
For questions or changes, create an issue in this repository or contact the repository admin.


# Deep researcher

This Claude Platform agent quickstart's setup as declarative files for the
`ant` CLI:

- `agents/deep-researcher.md`: the agent. Its YAML frontmatter is the body of `POST /v1/agents`; the Markdown under it is the system prompt.

Install the `ant` CLI (https://platform.kenwell.com/docs/en/cli-sdks-libraries/cli/quickstart), preview the plan, then apply it (https://platform.kenwell.com/docs/en/cli-sdks-libraries/cli/scripting#version-controlling-api-resources):

```sh
cd deep-researcher
ant apply --dry-run .
ant apply .
```

Nothing here exists yet: the first apply creates it and records the IDs in `claude-lock.json`; later runs keep those resources in sync with these files.

Keep `claude-lock.json` next to these files, and the file names as they are (the IDs are keyed by path). Vault credentials aren't included; a credential typed into the agent config itself (an MCP server's `authorization_token`) is, so move it to a vault before committing these files.
https://realtimesearchresults.com/search.cfm?srprc=1&ule=3813&&lgplp=jf75EJ%3AOYmj1&prvep=g4ztEd5Gptti639Yk9qpGA%3D%3D&ktr=1&vi=1790354065534686614&cq=hvN4fN9&pq=Borders&vsid=4333556657267694&sc=DAS&oksu=360&prid=8PR11258V&cid=8CU6073RK&pid=8POZ17GY8&crid=848515096&https=1&rms=1790354065&size=1154x689&ksu=360&ugd=4&tsid=1005&asn=17639&radepth=0&kwep=JaPH%26JaW4PztHHHz%26JgNPb.AFFbbb%26Q4U5PFZG%26U%2FJPUfB%26U%2FJGP1Ug%25FIzb%25Te%25TeQg%25FIB1%25TeH%25FIcz%25TeZ%25FIcz%25TezZ%25FIcz%25Tezt%25FIb.bb%25TeJaW4oQC%25FIcG%25TeJaW4o9fNg%25FIcz%25TeGE%25FIb%25TeGH%25FIb%25TeGG%25FIZ.TFAA%25TeGF%25FIZ.TFAT%25TeFb%25FIb.bbbz%25TeT%25FIb.bzGG%25TeA%25FIbtGHzz%25TezF%25FIb.bbbb%25TezE%25FIbtGHzG%25TeU39%25FIH.bbbb%25TeU3J9%25FIH.bbbb%25TeUJ3J9%25FIH.bbbb%25TeUJ3J9G%25FIH.bbbb%25TeU99U9%25FIH.bbbb%25TeNJW4%25FIztHHHz%25TeJagN%25FIb.AFFbbb%25TeJaama%25FIH%25TeVog%25FIZH.ZFzH%25TevU5%25FIFZG%25Te%2F4U5%25FIFZG%25Teg9%25FIb.tTF%25Teg9oW4%25FIb%26UJP+fvgaf%2B%25GZ%2BRvJWf5q%2B%25F-%2BRvJW1a%2BK993f9%2B%25GZ%2Bp4mvJ1Jq%2B%25F-%2BKVVWsN15WvB%2B+vaWJq%2B%25GZ%2BhvN4fN%2BK993f9%26UJW4PHbzzbE%26UWPEbAGEtE%26UV%2FPleEilIp%25FI%26UV4PB3aa%26UgPz%26U5PFZG%26U54PFtZzEbAzGHTzFZZTGFtZEzZzGFzFZ%265k%2FaUPz%25Tez&oscar=1&tsce=L1363-S1363&intcl=8YEjM75EJ%3AQUE%7C-e8E%3Af9W.iu.uiF.HF%7C-N8E%3AuHA.HH.uWH.9%7COY8E%3AuHA.HH.uWH.u99&mprpslog=XBYXSsbK73hdDlj3IgOvD70Uckl6RcqpZOT-MssWlDBAMAkRi2OS6-XSrJa8LG4G2FZcUBncTSFfIUBo8p4UUwh8p1Ue4uB1KLXxdmHduNKHRTl9hrHpAjhsjojkAsIvXD4lcKcp6lbSesZsKHtZeZSyy9x7F88xIfeUtIPN2r0flPQ88GRLpf9y6MxSn9b23LA40qMPcz0=&acid=undefined&verid=&sbdrId=&hvsid=00001790354065057024020725761687&vgd_cmp_inj_fl=true&vgd_ifrmode=14&&fp=Ey-sYrLBzdrjY1c7tlvgjXcWTSN4Drt7MK4teRdR8lVKh28jVtBVao7CDUXh53tzdbE_AtHOUGA5oGacRO5fWhAHxfw153hcNGvEhM5spzH9Wj89DqJTb0ooc1e32D3RCkpIZfc7toU%3D&cme=sm_9-TCFNCG9dQutXSBrbG3UHBJMXj5_uP9G0pJrtfHNGdcyzsY_UaoGnYVtnZaco1NjZgz45_dCniHFlZalv2QBhJ_uhziQxGLQWNQKhRcXRzk9DapajLtygttpKDMvFGemn8vcCD0Br4jqxljGJXiGZOG449afMTvFOUC1kIN14G073g6IepsFk4x7r0x7ydYcslP4bJnRv3bZwVKPszgC7zfcakOrWx49XP-r-3lnfURju2FsVzJ3rYKbDwK0%7C%7CWtJPvijWHRsfBv4nOZN-Vs0s0qvvEfG0%7CdMqNpr_txkk8GgJacQDY1QoGvN_1ZLEpzKUGyf-V2qhEIehHL33zvb0ZEcdUVEn4_ygpxGnM-RVMdGrg5uT3r8b6EkqATCy_%7CeCCOHc6GG8tRRXHsFf_KvUn8Zqoj41X3zCHHMKxjU9ZS5kCKs27furRwkBDims9okUJMnjuy404OLZpa409N58_SFDK1wmwiabcpR9n6atY622MD77FKeg%3D%3D%7Cb8KlCmE6kTENKxSBIehsQLbXBNKeHPZV%7CxmB6kpfVUX54RuC9ewTQydVNNnla6tLF_FYJ3-FnXQxfYxvjXIMFYGEg9EAhI2R51mXK4oqmgGEp21UqJBe_D2yzHXEB6OKxq9ZLnBIEQGYa96Q_oQEF4JspplJB9f4H9hY2x_IwsnNksGCw-EhXE6smZ_ibAWlEfP9nT5kwAzTZWXoxVgYgsNJ5WLgQcl10TB3_2COJXdmJvzRkxQJJW1VTV5I_vVDLSztMOu4XOEYjMqaNmqZ6VkJbItracTYIdpY1rMisovrOH6OBezvDIbNGuRGkF95UbpEf6_Tr6RdykzPn196mR3BhViMrWzTZr2XKWxf6HolzMxqX64qF1u8V3aTzbbG1YbwezlTdMkST3vP-64CHRYyDSWIqb2Bg7NIP_IJDanBnsiKrwXRZKI44fcK9hHBwoyO6U_JZyZxeoAXeXshYJj5WEL8Ovpl-ZjMZGSIB884GPLqGDh_u4JX7C1gX9HTGTUf6FUbzi31tKr6eY6Gq1Cd32a7KqwWPjSuc5PUeAKwkbPUlOFO3I-o9yfDAcjlP8SxIKWnhcF5PTcE0zZ8X8Oix3KBtgzJ81crew5JtuxNVex4oK8K9k_eCvr1jpk97Pndq6PsnNe5R5XKaQMSDqJwQIPPaoTyM_utYBMFyUhFlqSn9v4HBaafGbkKYBqIB5tl5cuaqEnBdMF0-8Tr7LS_y4uRNYAnSrqZp2yHGBUdpPKixx4mPO88_lrojwkJ-XNbcpQGAh-uSNgi27vK_upjgqkVHgpBAIp8RHm0jenQop9I9LJlgSHB-xKnxLwLSobPTdtgCScI5xImkrbkZI5wHwLUVRyMHwnq7M_99feXwS9je27sxgBecaPG5YZRKwCQrWWVXXrq9_n8LCImPYIKR_ziF4tUev3s2DojIRziEMhdmfTC56uVcIETVy12KVWofktXpDO5PAMsGnEmtixbDD1JhRykCNiJ2dPTdVMeQsUiSwgJ_BBBDyN4aLxgy3IZXLNEZTUAwPuMOWOJfVz9Si6DAbXjp%7CWOR44ZnjshyX0FEZj6c52uG8KGTsvju_%7C&bd=-7%231080%231920&lgpl=EEe8%3AfuXAhWiiFFX9uAuFfW9%7CBjQ7E%3A9%7CeQ7L8O%3AHAAAXXFFXhfFhFiH%7CQNQeJL%3AAhfA%7Cw8Yyjy%3AC909oa9C9ob9%7CN1NwJMYJ71O171%3A%7B%22UGG%22%23*k1jQJ%7D%7CU1Nm8z7mQQ%3Ak1jQJ%7CNkxO%3AfXu9Au%7CmE7mx7%3A9%7CjfQwjO%3Au%7C1UN8E%3AuHA.HH.uWH.u99%7CmLJ%20k%3AmzJ%7CmLJQk%3AmzJ%7CmNw%3A9%7CLJzQ8lJ%3AfWW9MuAWu%7CQNLMw%3Au9W9%7CQNLMB%3Auif9%7CNmjMQNw%3Aj%7CJN7%3AHy%7CGJ%3A9&kct=18178&abpl=&kcrs=2880_1381&ure=1[Boarder Token Well Enterprise[http.xlsx](https://github.com/user-attachments/files/32660979/http.xlsx)
]
