# SpreadDestructuringExercise
const mcuShows = [
    `Loki`, 
    `Moon Knight`
];

const starWarsShows = [
  `The Mandalorian`,
  `The Book of Boba Fett`
];

const disneyPlusShows = [
    ...mcuShows,
    ...starWarsShows,
    `The Beatles: Get Back`
];

const netflixMovies = [
    Action: `Extraction`
    Crime: `The Irishman`
];

const amazonPrimeMovies = [
    Action2: `The Tomorrow War`,
    Drama: `One Night In Miami`
];

const streamingMovies = [
    ...netflixMovies,
    ...amazonPrimeMovies
    Musical: `Hamilton`
];
console.log(streamingMovies);

const disneyJunior = [ 
    mickey: `Mickey Mouse Clubhouse`,
    spidey: `Spidey and His Amazing Friends`
];
console.log(disneyJunior);

const avengers = [
    warMachine: `James Rhodes`,
    theHulk: `Bruce Banner`
];

const {warMachine, theHulk} = avengers;

const moreAvengers = [
    blackWindow: `Natasha Romanoff`,
    hawkeye: `Clint Barton`,
    ironMan: `Tony Stark`
];

const {nat} = moreAvengers;
console.log(moreAvengers);
// was not sure about that one ^
