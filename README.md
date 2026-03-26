## ```About me```

```json
{
  "name": "Lucas Dias Noronha",
  "role": "Data Science & AI Student",
  "education": [
    "B.Sc. in Data Science and Artificial Intelligence",
    "Technologist in Artificial Intelligence",
    "Technologist in Data Analysis"
  ],
  "stack": {
    "languages": ["Python", "R", "C"],
    "ml_dl": ["TensorFlow", "PyTorch", "Scikit-learn"],
    "tools": ["Docker", "Git", "Linux", "Bash"],
    "cloud": ["AWS", "Azure"]
  },
  "interests": [
    "Machine Learning",
    "Statistical Modeling",
    "Data Engineering"
  ]
}
```
```sql
CREATE TABLE articles (
    id INTEGER PRIMARY KEY,
    title TEXT NOT NULL,
    url TEXT NOT NULL,
    platform TEXT,
    published_at DATE
);

-- Inserção dos seus artigos
INSERT INTO articles (id, title, url, platform) VALUES
(
    1,
    'Inteligência Artificial: Dos Primórdios até a Atualidade',
    'https://medium.com/@lucasdiasnoronha1/inteligência-artificial-dos-primórdios-até-a-atualidade-afb6b7af8451',
    'Medium'
),
(
    2,
    'A Relevância da Álgebra Linear e Estatística no Machine Learning',
    'https://medium.com/@lucasdiasnoronha1/entendendo-a-relevância-da-álgebra-linear-e-estatística-para-o-aprendizado-de-máquina-907df28655ff',
    'Medium'
);

-- Consulta para visualizar os artigos
SELECT title, url
FROM articles
ORDER BY id DESC;
```
