


### to add submodules 

``` shell
git init
git remote add origin https://github.com/Biks2013/AITutorialsCollection.git
git submodule add https://github.com/FullStackRetrieval-com/RetrievalTutorials.git FullStackRetrieval-com/RetrievalTutorials
git submodule add https://github.com/langchain-ai/rag-from-scratch.git langchain-ai/rag-from-scratch
git submodule add https://github.com/karpathy/nn-zero-to-hero.git karpathy/nn-zero-to-hero
git submodule add https://github.com/karpathy/micrograd.git karpathy/micrograd
git submodule add https://github.com/aritrasen87/LLM_RAG_Model_Deployment.git AritraSen/LLM_RAG_Model_Deployment
git submodule add https://github.com/0xmerkle/lcel-deepdive-runnables.git 0xmerkle/lcel-deepdive-runnables
git submodule add https://github.com/Coding-Crashkurse/LCEL-Deepdive.git Coding-Crashkurse/LCEL-Deepdive
git submodule add https://github.com/BikS2013/ShawhinT-YouTube-Blog.git ShawhinT/YouTube-Blog

rem git submodule add https://github.com/ShawhinT/YouTube-Blog.git ShawhinT/YouTube-Blog


git commit -m "initial commit"
git push -u origin master

``` 


### to clone the complete repo including submodules


``` shell
git clone https://github.com/Biks2013/AITutorialsCollection.git
cd AITutorialsCollection
git submodule update --init --recursive
``` 

### alternatively 

``` shell   
git clone --recurse-submodules https://github.com/Biks2013/AITutorialsCollection.git
```
