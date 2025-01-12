# Introduction

Vue Test Utils est la bibliothèque officielle de tests unitaires pour Vue.js.

Voici la documentation de Vue Test Utils v1, qui vise Vue 2 et les versions antérieures.

En bref :

- [Vue Test Utils 1](https://github.com/vuejs/vue-test-utils/) ciblant [Vue 2](https://github.com/vuejs/vue/).
- [Vue Test Utils 2](https://github.com/vuejs/vue-test-utils-next/) ciblant [Vue 3](https://github.com/vuejs/vue-next/).

  <div class="vueschool"><a href="https://vueschool.io/courses/learn-how-to-test-vuejs-components?friend=vuejs" target="_blank" rel="sponsored noopener" title="Learn how to use Vue Test Utils to test Vue.js Components with Vue School">Apprenez comment tester les composants de Vue.js avec Vue School</a></div>

- [Installation](./installation/)
- [Guides](./guides/)
  - [Pour commencer](./guides/getting-started.md)
  - [Les Conseils pratiques](guides/common-tips.md)
  - [Test des touches, de la souris et d'autres événements DOM](guides/dom-events.md)
  - [Tester le comportement asynchrone](guides/testing-async-components.md)
  - [Utilisation avec TypeScript](guides/using-with-typescript.md)
  - [Utilisation avec Vue Router](guides/using-with-vue-router.md)
  - [Utilisation avec Vuex](guides/using-with-vuex.md)
  - [Bibliothèques utiles pour les tests](guides/useful-libraries-for-testing.md)
- [API](api/)
  - [mount](api/mount.md)
  - [shallowMount](api/shallowMount.md)
  - [render](api/render.md)
  - [renderToString](api/renderToString.md)
  - [Mounting Options](api/options.md)
    - [context](api/options.md#context)
    - [slots](api/options.md#slots)
    - [scopedSlots](api/options.md#scopedslots)
    - [stubs](api/options.md#stubs)
    - [mocks](api/options.md#mocks)
    - [localVue](api/options.md#localvue)
    - [attachToDocument](api/options.md#attachtodocument)
    - [attrs](api/options.md#attrs)
    - [propsData](api/options.md#propsdata)
    - [listeners](api/options.md#listeners)
    - [parentComponent](api/options.md#parentComponent)
    - [provide](api/options.md#provide)
    - [other options](api/options.md#other-options)
  - [Wrapper](api/wrapper/)
    - [attributes](api/wrapper/attributes.md)
    - [classes](api/wrapper/classes.md)
    - [contains](api/wrapper/contains.md)
    - [emitted](api/wrapper/emitted.md)
    - [emittedByOrder](api/wrapper/emittedByOrder.md)
    - [exists](api/wrapper/exists.md)
    - [destroy](api/wrapper/destroy.md)
    - [find](api/wrapper/find.md)
    - [findAll](api/wrapper/findAll.md)
    - [get](api/wrapper/get.md)
    - [html](api/wrapper/html.md)
    - [is](api/wrapper/is.md)
    - [isEmpty](api/wrapper/isEmpty.md)
    - [isVueInstance](api/wrapper/isVueInstance.md)
    - [name](api/wrapper/name.md)
    - [props](api/wrapper/props.md)
    - [setChecked](api/wrapper/setChecked.md)
    - [setData](api/wrapper/setData.md)
    - [setMethods](api/wrapper/setMethods.md)
    - [setProps](api/wrapper/setProps.md)
    - [setSelected](api/wrapper/setSelected.md)
    - [setValue](api/wrapper/setValue.md)
    - [text](api/wrapper/text.md)
    - [trigger](api/wrapper/trigger.md)
    - [isVisible](api/wrapper/isVisible.md)
  - [WrapperArray](api/wrapper-array/)
    - [at](api/wrapper-array/at.md)
    - [contains](api/wrapper-array/contains.md)
    - [exists](api/wrapper/exists.md)
    - [destroy](api/wrapper-array/destroy.md)
    - [filter](api/wrapper-array/filter.md)
    - [is](api/wrapper-array/is.md)
    - [isEmpty](api/wrapper-array/isEmpty.md)
    - [isVueInstance](api/wrapper-array/isVueInstance.md)
    - [setChecked](api/wrapper-array/setChecked.md)
    - [setData](api/wrapper-array/setData.md)
    - [setMethods](api/wrapper-array/setMethods.md)
    - [setProps](api/wrapper-array/setProps.md)
    - [setValue](api/wrapper-array/setValue.md)
    - [trigger](api/wrapper-array/trigger.md)
    - [isVisible](api/wrapper-array/isVisible.md)
  - [components](api/components/)
    - [RouterLinkStub](api/components/RouterLinkStub.md)
  - [Selectors](api/selectors.md)
  - [createWrapper](api/createWrapper.md)
  - [createLocalVue](api/createLocalVue.md)
  - [config](api/config.md)
