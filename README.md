# Google Integration Pack

Pack which allows integration with different Google services.

## Configuration

**Note** : When modifying the configuration in `/opt/stackstorm/configs/` please
           remember to tell StackStorm to load these new values by running
           `st2ctl reload --register-configs`

## Actions

* ``get_search_results`` - Retrieve Google search results for the provided
  search query.
