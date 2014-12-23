```
# install to /opt/openmetrics
cd /opt/openmetrics
git clone https://github.com/openmetrics/om-agent.git
cd om-agent
git submodule init
git submodule update
cd lib/ohai
rake install
```

