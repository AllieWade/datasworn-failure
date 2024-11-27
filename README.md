# datasworn-failure
This is an adaptation of the article [Learning From Your Failures in Starforged](https://tomkinpress.com/blogs/news/learn-from-your-failures-in-starforged) to [Datasworn](https://github.com/rsek/datasworn) 0.1.0, intended for use with [Iron Vault](https://ironvault.quest).

To use in Iron Vault, put failure.json in Iron Vault's homebrew content folder; enable homebrew content in the Iron Vault settings; and put the following line in your custom playset.

```
*:learn_from_failures/**
```

At that point your character should have a failure track and you should be able to call Mark Your Failure and Learn From Your Failures from Iron Vault's Make a Move command, as well as looking the moves up in the Iron Vault sidebar.

## Known Issues
- The failure track currently increments xp gained like the other legacy tracks instead of not doing that.
- Making the Learn From Your Failures move with prompts doesn't prompt or roll. You can still roll against the failure track by using Make a Move, then rolling a custom progress roll against the failure track.

## License
This project is licensed under the [Creative Commons Attribution 4.0 International license](https://creativecommons.org/licenses/by/4.0/) and owes basically everything to other peoples' hard work.
