# Dataframe Summit 2020

## Discussion topic ideas:

- **High level overview for each project represented**. No demos/sales pitches, just high level technical capabilities and perhaps goals for the next 1, 3, and 5 years and beyond. 5-10 min slide show each should suffice.
- **Dataframe definition and operators**: Everyone will be biased here, but I think we can have some interesting conversations around separating dataframe (not necessarily pandas) implementations from relational implementations or dataframe-like implementations. The point is to drill down the things that make dataframes unique versus relational systems. This is discussed in our paper, which maybe should be (briefly) presented or sent out in advance to have a jumping off point.
- **What would a dataframe query language standard look like?** We proposed an algebra in the paper attached, but that's not very useful for users from an API perspective. Something intuitive and concise.
- **What are your dataframe implementations used for?** Common use-cases will help with planning future optimizations. Along this note: how are users interacting with the system (e.g. notebooks, scripts, job manager, etc.)?
- **Topics specific to pandas**:
    - Should the problems pandas faces (API, maintainability, performance) be fixed in pandas, or is a new project needed (i.e. pandas2)?  
    - Is it useful for project to reimplement the pandas API? Why/Why not?    
    - How much (if at all) should pandas API change or be updated? Is the risk of splintering the pandas community/user base enough to warrant keeping the API as it is? After all, pandas users do not have a problem with the API when surveyed.
    - Since so many libraries depend on pandas, does it make sense for pandas to define a standard for dataframe interaction (API) for Python? This can be a new API or the existing API. What would such a standard look like?
