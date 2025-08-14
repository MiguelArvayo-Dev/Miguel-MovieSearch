Movie Search

This excercise is a movie search app using API http://www.omdbapi.com,
this app will display movie posters, name and release year from the fetch JSON
also you can sort the movies by title

this exercise uses:

useCallback - to avoid repeating search on each render
useMemo - to avoid recomputing the sorting of movies
useRef - to obtain users inputs
custom hooks - for the data fetch
conditional rendering - in case of movies not found and loading on slow connection
