# Vue Schedule

[AN - anotation]
[SF - stand for]

- Installation
  => NodeJS
  => Vue CLI
  => Init a Vue project

- Core
  => Vue Instance
  => Go through lifecycle

- Template syntax
  => Interpolations [AN] {{}}
  => Go through directives 

- Options of Vue instance & directives
  => data
  => methods
  => computed
  => Compare [methods / computed]
  => watcher
  => Other directives:
    => v-bind [SF] :<attribute>
    => v-on [SF] @<event>
    => v-if & v-show
    => v-for

- Event handling
  => Pass params and $event
  => Event modifiers
   => [.prevent] - The submit event will no longer reload the page
   => [.stop]   
   => [.capture]
   => [.self]   
   => [.once]   
   => [.passive]

- Form input binding
  => v-model directive
  => Value bindings
  => Modifiers
    => [.lazy]
    => [.number]
    => [.trim]

- Components
  => Introduce
  => Pass props to child component
  => Pass events to child component & emit to parent component
  => [is] attribute
  => register local & global components
  => Custom events
    => [.native] modifier
    => [.sync] modifier
  => Slot [AN] <slot name="name"> & <template v-slot:name>

- Lifecycle hooks
  => [beforeCreate]
  => [created]
  => [beforeMount]
  => [mounted]
  => [beforeDestroy]
  => [destroyed]

- Reusability
  => Mixins
  => Plugins
  => Custom directives (self-explore)

- Vue router