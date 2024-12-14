// 34: have the logger service running in docker, whendoing make up build we will have the 
// updated broker service running in docker, now we modify the frontend to make a call to this broker saying log this information

//35: have logger and authentication service running in background, need to keep a record of when ppl log in and out from a site, add logic in the authentication service to communicate w the logger service everytime sb successfully authenticates (log when sb authenticates)