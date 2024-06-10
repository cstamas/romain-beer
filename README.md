# Romain buys the beer on next meetup

Build fails with normal local repo, to try:
```
mvn clean install -Dmaven.repo.local=nonsplit
```

But, build succeeds with split local repo:
```
mvn clean install -Dmaven.repo.local=split -Daether.enhancedLocalRepository.split=true -Daether.enhancedLocalRepository.splitRemoteRepository=true
```
