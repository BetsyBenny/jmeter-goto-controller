# JMeter GoTo Controller

A custom JMeter plugin that jumps to a target 
Transaction Controller when any sampler fails.

## Features
- Detects sampler and assertion failures
- Jumps to selected Transaction Controller on error
- Executes target TC once then stops thread
## Installation
1. Copy goto-controller.jar` to `<JMeter_Home>/lib/ext/`
3. Restart JMeter

## Usage
1. Add GoTo Controller under Thread Group
2. Add Transaction Controllers inside it
3. Select target TC in the dropdown
4. Run test — on any failure it jumps to target TC
