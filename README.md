Things to do:
- work out _helpers.tpl
- add deployment for confluence container
- add cassandra database
- test out connecting the confluence container with the DB!
- add a little guide !

Things to remember to do:
- force git add a .keep file in confluence-home

Steps to run:
1. 
```
helm install confluence .
```
2. When your confluence pod is ready, port forward it.
3. With the port forward running, access your confluence web GUI by looking at [http://localhost:8090⁠](http://localhost:8090/).
4. When viewing localhost, you will see this page:
![screenshot of Confluence page asking for a license](./images/localhost-request-license.png)
so:
5. Get a trial Confluence license by following the link in the page. Here is also a [Guide From Confluence on the topic](https://support.atlassian.com/confluence/kb/how-to-generate-an-evaluation-or-trial-license-for-confluence-data-center/).
6. Enter your license key into the web GUI