# less
Less styleguide

##Naming
Name variables descriptively. (bad: @white-color: #fff; good: title-color: #fff; )

##Nesting
Avoid too much nested styles. Max 3-4 levels are recommended.
Use comma-separated selectors with caution and only where it is really needed. Do not use comma-separated selectors nested in other comma-separated selectors.

##Mixins
Use only parametrized mixins. Keep your mixins small.

##Included files
Base files (files, which are included in other files) should contain only variables and parametrized mixind so they do not render to CSS.
