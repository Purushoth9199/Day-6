1.Write a constructor for the class Movie, which takes a String representing the title of the movie, a String representing the studio, and a 
String representing the rating as its arguments, and sets the respective class properties to these values.

class movies {
    constructor(title, studio, rating) {
      this.title = title;
      this.studio = studio;
      this.rating = rating;
    }
  
    getrating() {
      return "the movie rating is" + this.rating;
    }
  }
  
  
  
  
2. Write a piece of code that creates an instance of the class Movie with the title “Casino Royale”, 
  the studio “Eon Productions”, and the rating “PG13”
  
  
  class movie {
    constructor(title, studio, rating) {
      this.title = Casino Royale;
      this.studio = Eon Productions;
      this.rating = PG13;
    }
