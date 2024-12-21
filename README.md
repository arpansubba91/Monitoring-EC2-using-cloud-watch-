This guide explains how to create an AWS CloudWatch dashboard and add widgets to monitor EC2 resources.
Step 1: Accessing the AWS Management Console
- Log in to your AWS Management Console.
- Search for 'CloudWatch' in the Services menu and open it.
Step 2: Creating a CloudWatch Dashboard
1. Go to Dashboards:
- In the CloudWatch console, select 'Dashboards' from the left-hand menu.
- Click the 'Create dashboard' button.

2. Enter a Dashboard Name:
- Provide a name for your dashboard, such as 'EC2-Monitoring'.
- Click 'Create dashboard'.
Step 3: Adding Widgets to the Dashboard
1. Choose a Widget Type:
- After creating the dashboard, you’ll see a prompt to add a widget.
- Select the widget type you want to use: Line, Number, Gauge, etc.
- Click 'Next'.

2. Select Metrics for the Widget:
- Click 'Browse' under the metrics selection.
- Navigate to 'EC2' -> 'Per-Instance Metrics'.
- Select the metrics you want to monitor, such as:
 - CPUUtilization (for CPU usage).
 - NetworkIn and NetworkOut (for incoming and outgoing network traffic).
 - DiskReadBytes and DiskWriteBytes (for disk I/O activity).

3. Customize the Widget:
- After selecting the metric, configure the display options
 

4. Repeat for Additional Widgets:
- Add widgets for all metrics you want to monitor by repeating the steps above.
Step 4: Save the Dashboard
- After adding all the desired widgets, click 'Save Dashboard'.
