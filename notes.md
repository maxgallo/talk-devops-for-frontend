# Part 1

Context: TV world at DAZN
- 25+ different devices running html5 applications
- features
    - common features
    - per device feature
- The previous approach
    - feature teams
    - device teams
- Problems of the approach
    - device teams not working on real features, not being able to fix issues
    - feature teams not testing / caring about devices
    - handover for each feature
    - end to end work hard to track (multiple teams involved)

# Part 2

DevOps
"The First Way emphasizes the performance of the entire system, as opposed to the performance of a specific silo of work or department."

view of the entire system

- slide: laptop on the left -> customers on the right
![feature](./images/features_devices.png)
- EUREKA! -> I've already seen this one, it's DevOps
- DevOps: Development & Operations teams were indipendent squads, each own with its own goal

Official Definition: "a software engineering culture and practice, that aims at unifying software development and software operation."

this was possible because of abstractions (servers)
- AWS or a "Platform" team that leveraged some of the operation tasks to allow a dev team to become more ops

If we create an abstractions on the devices differencies we can allow feature team to deploy their feature in production

# DevOps for Frontend

We created two different abstractions
- Runtime -> Bootstrap (keycode, networking, background/foreground, even time)
- Tool (develop on device, debugging, unified approach, monitoring)
- Testing on devices

"TV Platform" team and Feature teams

- updated diagrams of laptop -> customers

Maximise the flow / Lead Time (change lead time)
- Make work visible: single team Jira board
- Reduce batch size: up to the feature teams
- Prevent defect being passed downstream: developing on devices, automation for testing
- always optimise for the global goals: YEY

-->

