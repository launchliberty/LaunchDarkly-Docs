An experiment is a running tally of user behaviors based on which variation of a feature flag they receive. In LaunchDarkly, an experiment requires two things: a metric that defines what user behaviors to track, and at least one flag associated with that metric.

Experiments are largely managed via PATCH requests to the Flags API. There are also dedicated API resources for getting and deleting experiment data.
