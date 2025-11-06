# device-dashboard
Easy Device Filtering
Target Users
•       IT Operations Teams: Monitor overall health and respond to alerts
•       Support Engineers: Troubleshoot specific device or location issues
•       Network Operations: Identify network-related performance degradation
•       Collaboration Administrators: Plan capacity and evaluate device deployment strategies
•       IT Leadership: Track KPIs and justify infrastructure investments

 
Goals & Success Metrics
Primary Goals
1.     Reduce Mean Time to Resolution (MTTR) for Teams Room issues by 70%
2.     Enable proactive identification of performance issues before user impact
3.     Provide multi-dimensional analysis across geographic, organizational, and technical dimensions
4.     Deliver executive-ready reporting on collaboration infrastructure health and ROI
Success Metrics
Metric	Target
Dashboard Load Time	< 2 seconds for 10,000 devices
Filter Response Time	< 500ms for any facet combination
User Adoption Rate	80% of IT operations teams within 60 days
MTTR Reduction	70% reduction from baseline
Customer Satisfaction Score	NPS > 50
 

 
Core Features & Requirements
Multi-Dimensional Faceted Filtering
Required Filter Dimensions
Dimension	Data Source	Example Values
Country	Location taxonomy	USA, UK, Germany, France, Japan
City	Location taxonomy	New York, London, Tokyo, Sydney
Building	Location taxonomy	HQ Building A, Branch Office, Data Center
Manufacturer	Device metadata	Microsoft, Logitech, Poly, Crestron, Yealink
Device Type	Device metadata	Teams Room Standard, Teams Room Premium, Teams Display, Teams Phone
Subnet	Network topology	10.1.0.0/24, 192.168.100.0/24
VLAN	Network topology	VLAN 100 - Conference Rooms, VLAN 200 - Executive
Business Unit	Custom tags	Sales, Engineering, HR, Finance
VIP Status	Custom tags	Executive Conference Room, Board Room, All Hands
 
Filter Behavior Requirements
•       Cascading filters: When a Country is selected, City filter should dynamically update to show only cities in that country
•       Multi-select support: Allow selection of multiple values within a single dimension (e.g., USA + UK + Germany)
•       Filter persistence: Maintain filter state when switching between dashboard views
•       Clear all filters: Single-click ability to reset all filters to default state
•       Filter state indicators: Visual indication of active filters and filtered result count

 
Dashboard Views & Visualizations
Overview View
Primary landing page providing high-level KPIs and distribution metrics.
•       Key Metrics Cards:
•          • Average Quality Score across all filtered devices
•          • Poor Call Percentage with total call volume
•          • Count of devices with quality issues (score < 80)
•          • Geographic coverage summary
•          • Week-over-week trend indicators for each metric
•       Performance by Manufacturer Bar Chart:
•          Horizontal grouped bar chart showing average quality score per manufacturer
•       Device Distribution Pie Chart:
•          Distribution of device types across filtered results
•       Quality vs Poor Call Comparison:
•          Dual-axis bar chart comparing quality scores and poor call percentages by manufacturer
Geographic Analysis View
•       Quality Heatmap by Country:
•          Color-coded horizontal bar chart showing average quality by country (green > 85, yellow 75-85, red < 75)
•       Regional Deployment Cards:
•          Grid of cards showing device count, average quality, and health status per region
•       City-Level Drill-Down:
•          Expandable view showing quality metrics at city and building levels
Trends View
•       30-Day Quality Trend:
•          Line chart showing daily average quality score over 30 days with confidence bands
•       Poor Call Percentage Trend:
•          Line chart tracking poor call percentage over time
•       Network Latency Trend:
•          Line chart showing average network latency trends
•       Anomaly Indicators:
•          Visual markers on trend lines indicating PEWMA-detected anomalies
Comparative Analysis View
•       Manufacturer Performance Comparison:
•          Multi-metric bar chart (quality score, poor call %, device count) grouped by manufacturer
•       Device Type Performance:
•          Side-by-side comparison of Teams Room Standard vs Premium vs Display vs Phone performance
•       Advanced Query Results:
•          Pre-built query widgets showing:
•          • Devices by manufacturer in specific regions with poor call rates > 10%
•          • Premium vs Standard device type quality comparison
•          • Subnet with highest quality variance
Outlier Detection View
•       Devices Requiring Attention Table:
•          Sortable, filterable table showing devices with quality scores > 1.5 standard deviations below average
•          Columns: Device ID, Location, Manufacturer, Type, Quality Score, Poor Call %, Subnet
•       Quality Score Distribution Scatter Plot:
•          X-axis: Quality Score, Y-axis: Poor Call Percentage, each point represents a device
Network Correlation View
•       Quality vs Network Metrics Scatter Plot:
•          X-axis: Latency (ms), Y-axis: Quality Score, color-coded by quality threshold
•       Packet Loss Impact Analysis:
•          Scatter plot showing correlation between packet loss percentage and quality score
•       Network Health by Subnet:
•          Top 10 subnets ranked by device count with average quality and latency metrics

