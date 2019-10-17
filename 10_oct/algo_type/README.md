# Exo 1 pseudo code

Réaliser l’aglo permettent de calculer une moyennne de notes :

- Une variable pour demander à l’utilisateur d’ajouter une note
- Une variable pour stocker les notes
- Une fonction pour calculer la moyenne

```
ALGORITHME note_average

 new_note: STRING
    notes: ARRAY<INTEGER | FLOAT>

    FUNCTION get_result(): INTEGER | FLOAT
        // Déclaration
        total: INTEGER | FLOAT
        i: INTEGER

        START
            // Exécution
            total <- 0
            FOR i FROM 0 TO notes.LENGTH [ i <- i + 1 ]
                total <- total + notes[i]
            END FOR

            RETURN total / notes.LENGTH
        END
    END FUNCTION

START
  new_note <- PROMPT("Ajouter une note")
  notes <- notes + [PARSEINT(new_note)]
  get_result()
END

```

# Exo 2 pseudo code

Créer un aglo qui permet de calculer l'année de naissance d'un utilisateur

`````
ALGORITHME get_birth_year
    user_age: STRING
    current_year: INTEGER

    FUNCTION get_result(age: INTEGER): INTEGER
        START
            return current_year - age
        END
    END FUNCTION

START
  current_year <- 2019
  user_age <- PROMPT("Quel est votre age")
  get_result(user_age)
END
````
`````
