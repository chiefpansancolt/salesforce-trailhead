# salesforce-trailhead
Items completed apart of trailhead


## Get Access Token
- `System.debug(URL.getOrgDomainUrl());`
- `System.debug(UserInfo.getOrganizationId() + '!' + UserInfo.getSessionId().substringAfter('!'));`

`export SF_ACCESS_TOKEN='<TOKENHERE>'`
`sf org login access-token -r <URLHERE> -s -a <ALIASNAME>`