# Create a directed graph
graph = Digraph(format='png')
graph.attr(rankdir='LR', size='10,5')

# Define nodes for Back-to-Port Infrastructure
graph.node('1', 'Clear Site and Level Ground')
graph.node('2', 'Connect Utilities')
graph.node('3', 'Excavate Trenches')
graph.node('4', 'Install Drainage Pipes')
graph.node('5', 'Inspect Drainage System')
graph.node('6', 'Install Fire Hydrant Systems')
graph.node('6.1', 'Certify Firefighting Systems')

# Define nodes for Superstructure
graph.node('7', 'Lay Foundation')
graph.node('8', 'Erect Columns and Walls')
graph.node('8.1', 'Install Flooring and Roofing')
graph.node('9', 'Install Electrical & HVAC Systems')
graph.node('10', 'Finalize Interior & Exterior')

# Define nodes for Equipment Installation
graph.node('11', 'Assemble and Erect Cranes')
graph.node('12', 'Connect Power to Cranes')
graph.node('13', 'Install Auxiliary Systems')
graph.node('13.1', 'Calibrate Auxiliary Systems')
graph.node('14', 'Install Safety Systems')
graph.node('14.1', 'Certify Safety Systems')
graph.node('15', 'Perform Operational Tests')
graph.node('16', 'Stakeholder Walkthrough')

# Define edges for Back-to-Port Infrastructure
graph.edge('1', '2')
graph.edge('1', '3')
graph.edge('3', '4')
graph.edge('4', '5')
graph.edge('5', '6')
graph.edge('6', '6.1')

# Define edges for Superstructure
graph.edge('2', '7')
graph.edge('7', '8')
graph.edge('8', '8.1')
graph.edge('8.1', '9')
graph.edge('9', '10')

# Define edges for Equipment Installation
graph.edge('8.1', '11')
graph.edge('11', '12')
graph.edge('12', '13')
graph.edge('13', '13.1')
graph.edge('13.1', '14')
graph.edge('14', '14.1')
graph.edge('14.1', '15')
graph.edge('15', '16')

# Render and save the graph
graph.render('/mnt/data/Workflow_Critical_Path', format='png', cleanup=True)
