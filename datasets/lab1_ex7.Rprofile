.First <- function() {
  message("Type go() and hit Enter to get started!\n")
  
  go <<- function() {
    source(".init.R")
    file.edit("lab1_ex7.2.Rmd")
  rmarkdown::render("lab1_ex7.2.Rmd")
  rstudio::viewer("lab1_ex7.2.html")
    }
}


