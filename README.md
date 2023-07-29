# GRAPH-SERIES


this is just sample form taking input for graph for any cp question or DSA related question

**NORMAL GRAPH QUESTIONS INPUT TEMPLATE**
```
 int helper(vector<vector<int>> edges,int n) {
        int m=edges.size();
        vector<int>adj[n];
        //make Adjacency list
        for(int i=0;i<m;i++){
            adj[edges[i][0]].push_back(edges[i][1]);
        }
        write logic here
 }
int main() {
	int n,m;
	cin>>n;
	cin>>m;
	vector<vector<int>>edges(n,vector<int>(2));
	for(int i=0;i<m;i++){
		int p,q;
		cin>>p>>q;
		edges.push_back({p,q});
	}	
cout<<helper(edges,n);	
}

/*
input format
1- based indexing
for directed graph
11
13
1 2
1 9
1 8
2 3
3 4
4 5
5 1
6 1
9 10
10 11
11 1
5 6
6 7
*/

you can check the graph from below link
```
<img align="center" width="500" height="500" src="https://github.com/Akash242099/GRAPH-SERIES/assets/52275484/84620d42-bd25-451f-93a3-ee633bd16ee6">


keep learning
hurraaaah
