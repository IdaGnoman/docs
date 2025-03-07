---
title: Repository mit Themen klassifizieren
intro: 'Damit andere Personen Dein Projekt leichter finden und Beiträge dazu leisten können, kannst Du zu Deinem Repository Themen hinzufügen, die in Zusammenhang mit dem beabsichtigten Zweck, dem Themenbereich, verbundenen Gruppen oder anderen wichtigen Eigenschaften des Projekts stehen.'
redirect_from:
  - /articles/about-topics/
  - /articles/classifying-your-repository-with-topics
versions:
  free-pro-team: '*'
  enterprise-server: '*'
  github-ae: '*'
topics:
  - Repositories
---

### Informationen zu Themen

Mithilfe von Themen kannst Du Repositorys zu einem bestimmten Themenbereich erkunden, Projekte finden, zu denen Du einen Beitrag leisten kannst, und neue Lösungen für ein bestimmtes Problem entdecken. Themen werden auf der Hauptseite eines Repositorys angezeigt. Du kannst auf den Namen eines Themas klicken, um {% if currentVersion == "free-pro-team@latest" %}ähnliche Themen und eine Liste anderer Repositorys mit demselben Thema anzuzeigen{% else %}nach anderen Repositorys mit demselben Thema zu suchen{% endif %}.

![Hauptseite des Test-Repositorys, auf der Themen angezeigt werden](/assets/images/help/repository/os-repo-with-topics.png)

Rufe https://github.com/topics/ auf, um die am häufigsten verwendeten Themen zu durchsuchen.

{% if currentVersion == "free-pro-team@latest" %}Sie können Beiträge zum Satz an den enthaltenen Themen von {% data variables.product.product_name %} im Repository [github/explore](https://github.com/github/explore) leisten. {% endif %}

Repository-Administratoren können beliebige Themen zu einem Repository hinzufügen. Hilfreiche Themen, mit denen Sie ein Repository klassifizieren können, sind beispielsweise der beabsichtigte Zweck, der Themenbereich, die Community oder die Sprache des Repositorys.{% if currentVersion == "free-pro-team@latest" %} Zusätzlich analysiert {% data variables.product.product_name %} Inhalte öffentlicher Repositorys und erzeugt Themenvorschläge, die Repository-Administratoren annehmen oder ablehnen können. Die Inhalte privater Repositorys werden nicht analysiert, und es gibt keine Themenvorschläge für private Repositorys.{% endif %}

{% if currentVersion == "github-ae@latest" %}Internal {% else %}Public, internal, {% endif %}and private repositories can have topics, although you will only see private repositories that you have access to in topic search results.

Du kannst nach Repositorys suchen, die mit einem bestimmten Thema verknüpft sind. Weitere Informationen finden Sie unter „[Nach Repositorys suchen](/articles/searching-for-repositories/#search-by-topic)“. Sie können auch nach einer Liste von Themen auf {% data variables.product.product_name %} suchen. Weitere Informationen findest Du unter „[Themen suchen](/articles/searching-topics).“

### Themen zum Repository hinzufügen

{% data reusables.repositories.navigate-to-repo %}{% if currentVersion ver_lt "enterprise-server@2.22" %}
2. Klicke unter der Beschreibung des Repositorys auf **Add topics** (Themen hinzufügen). ![Link „Add topics“ (Themen hinzufügen) auf der Hauptseite eines Repositorys](/assets/images/help/repository/add-topics-link.png)
3. Gib das Thema ein, das Du zum Repository hinzufügen möchtest, gefolgt von einem Leerzeichen. ![Formular zur Eingabe von Themen](/assets/images/help/repository/add-topic-form.png)
4. Wenn Du mit dem Hinzufügen von Themen fertig bist, klicke auf **Done** (Fertig). ![Formular mit einer Liste an Themen und Schaltfläche „Done“ (Fertig)](/assets/images/help/repository/add-topics-done-button.png)
{% else %}
2. To the right of "About", click {% octicon "gear" aria-label="The Gear icon" %}. ![Gear icon on main page of a repository](/assets/images/help/repository/edit-repository-details-gear.png)
3. Under "Topics", type the topic you want to add to your repository, then type a space. ![Formular zur Eingabe von Themen](/assets/images/help/repository/add-topic-form.png)
4. After you've finished adding topics, click **Save changes**. !["Save changes" button in "Edit repository details"](/assets/images/help/repository/edit-repository-details-save-changes-button.png)
{% endif %}
