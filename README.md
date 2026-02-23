# Test_task_RCNI
Имеется список работ ученого (**groups**): https://orcid.org/0000-0002-8520-7267/allWorks.json?sort=date&sortAsc=false. В каждом списке приведено описание для 1 работы (как правило, это публикация). Для каждой работы может быть несколько описаний.

Необходимо извлечь массив со следующими характеристиками:
1. год издания **publicationDate>year**
2. название работы **title**
3. значения идентификатора типа **doi (workExternalIdentifiers >> значение externalIdentifierId** при условии, что **externalIdentifierType = doi**)
4. значения идентификатора типа **eid (workExternalIdentifiers >> значение externalIdentifierId** при условии, что **externalIdentifierType = eid**)
