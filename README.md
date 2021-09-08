- 👋 Hi, I’m @KARUN1421
- 👀 I’m interested in playing games
- 🌱 I’m currently learning webapps
- 💞️ I’m looking to collaborate on google
- 📫 How to reach me https://www.instagram.com/karun__varma/?hl=en

<!---
KARUN1421/KARUN1421 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
# Assignment02_Akkala
# KARUN KUMAR AKKALA
###### CHICAGO

>Chicago is the most **populous city in the U.S**. state of Illinois, and the third most populous city in the United States, following New York City and Los Angeles. Located on the shores of freshwater Lake Michigan. Chicago is an international hub for finance, culture, commerce, industry, education, technology, telecommunications, and transportation. I like this place because it is **flexible to all who live here** and also with good atmosphere.

-----

 ###### Direction to my favorite place
1. Maryville
2. Kansas City
    1. Kansas airport
    2. Terminal
    3. Airbus
3. Chicago
* Car
* Backpack
    * Camera
    * Good Clothes
* Food 
**[LinktoAboutMe.md](AboutMe.md)**

# Heading about creating a Table Food/Drinks

Introduction:
The following is to create a table with at least 4food/drinksthat you would recommend someone try.Include a short paragraph that introduces the table.

|Mandatory  |fav1     |fav2      |fav3     |fav4     |
| :-----:   | :-----: | :-----:  | :-----: | :-----: |
|Food/Drinks|Biryani  |Ice Cream |ThumsUp  |Mojito   |
|Location   |Kansas   |Chicago   |Denver   |Detroit  |
|Type       |Spicy    |Sweet     |cool     |Large    |
|Amount     |50-40    |40-30     |30-20    |20-10    |

-----
# quotes section
>"Education is not the learning of facts, rather it's the training of the mind to think".
>Author: *Albert Einstein* <br>
>"Strength is Life weakness is Death".
>Author: *Swami Vivekananda* <br>

-----
# Create a New Section about Code Fencing
>his article is about sets of vertices connected by edges. For graphs of mathematical functions, see Graph of a function. For other uses, see Graph (disambiguation).

A drawing of a graph.
In mathematics, graph theory is the study of graphs, which are mathematical structures used to model pairwise relations between objects. A graph in this context is made up of vertices (also called nodes or points) which are connected by edges (also called links or lines). A distinction is made between undirected graphs, where edges link two vertices symmetrically, and directed graphs, where edges link two vertices asymmetrically. Graphs are one of the principal objects of study in discrete mathematics. quick link to source code <https://en.wikipedia.org/wiki/Graph_theory#Graph>
```
int n;
vector<int> g[MAXN] ;
bool used[MAXN] ;
vector<int> comp ;

void dfs(int v) {
    used[v] = true ;
    comp.push_back(v);
    for (size_t i = 0; i < (int) g[v].size(); ++i) {
        int to = g[v][i];
        if (!used[to])
            dfs(to);
    }
}

void find_comps() {
    for (int i = 0; i < n ; ++i)
        used [i] = false;
    for (int i = 0; i < n ; ++i)
        if (!used[i]) {
            comp.clear();
            dfs(i);
            cout << "Component:" ;
            for (size_t j = 0; j < comp.size(); ++j)
                cout << ' ' << comp[j];
            cout << endl ;
        }
}
`````
quick link to source code<https://cp-algorithms.com/graph/search-for-connected-components.html>
