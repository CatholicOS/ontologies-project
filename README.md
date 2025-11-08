# Ontologies Project

Ontologies for the Common Digital Patrimony of the Catholic Church — formal `.owl` models defining entities, relationships, and vocabularies
for representing the Liturgy, Scripture, magisterial hierarchy, and foundational sources in a unified semantic framework.

## Submitting an Ontology Project

To submit an ontology project, please open an issue in this repository and fill out the form "Ontologies Project".

A repository will be created for your project following a convention such as `ontology-project-name`.

Usernames submitted via the form will be invited to the Catholic OS GitHub organization,
will be invited to a team in the Catholic OS GitHub organization,
and the team will be granted read / write permissions on the ontology project repository.

The base ontology definition should be in an ontology format agreed upon by the team that accepts to curate the project,
such as those listed here: [owl-format-variants](https://oboacademy.github.io/obook/explanation/owl-format-variants/).

Some common ontology editors are listed here: [Ontology editors](https://www.w3.org/wiki/Ontology_editors).

A common format is the `.owl` format (*Web Ontology Language*), and a common editor that supports this format is [Protege](https://protege.stanford.edu/software.php#desktop-protege).

The ontology definition should seek to follow the standards as laid out in the [OWL2 specification](https://www.w3.org/TR/owl2-overview/).

The team should curate a `README.md` file within the project repository for the ontology,
which should describe in greater depth the scope and the purpose of the ontology.

For example:

<!-- markdownlint-disable MD025 -->
> # Ontology of Foundational Sources of the Catholic Faith (`sources.owl`)
>
> This ontology defines the hierarchical and relational structure of the sources upon which the Catholic faith is founded and transmitted.
> It models the interdependence, authority, and contextual use of these sources within the living Tradition of the Church.
>
> ## Scope
>
> The ontology establishes formal classes and properties representing the primary and derivative loci of faith, including:
>
> - **Sacred Scripture**, as the divinely inspired Word of God and the foundational reference for all theological reflection;
>
> - **Sacred Tradition**, embodied in Magisterial Teaching, Liturgical Texts, and Canonical Law,
>   which together articulate the Church’s authoritative interpretation of Revelation;
>
> - **Sacred Wisdom**, as the Wisdom of the Saints and Church Fathers, expressing the lived experience
>   and theological insight of the faithful across ages;
>
> - **Theological and Scholarly Research**, as a derivative but essential domain of interpretive engagement
>   that deepens understanding within fidelity to Revelation;
>
> By formalizing these entities and their relationships—such as *derivesFrom*, *interprets*, *isAuthoritativeFor*, and *isCelebratedIn*—
> the ontology provides a semantic framework for reasoning about the sources of faith, their degrees of authority,
> and their role within the Church’s teaching and liturgical life.
>
> ## Purpose
>
> Its purpose is to support a clear interdependence and hierarchy of the sources upon which the Catholic faith is founded and transmitted,
> such that if the sources are submitted as training data for Large Language Models, the models can reason about the sources and their relationships,
> and the weights of the sources can be used to prioritize their authority.
<!-- markdownlint-enable MD025 -->

## Natural Language Web

While ***Protégé*** is an editor and model builder, further implementations of ontologies are welcome,
such as the [Natural Language Web](https://github.com/nlweb-ai/NLWeb).
***NLWeb*** (Natural Language Web Ontology Editor) is typically a natural language interface or assistant layer
designed to make ontology creation and querying more accessible.
