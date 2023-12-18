# NetworkedTicketSystem

A networked ticket trading system using Java, locks/semaphores and cloud-based Ticketmaster API. Integrated real-time data from Ticketmaster, enabling dynamic ticket sales and purchases while efficiently managing concurrent trades among ticket agents. The server, initiated by user input for schedule and agent files,  dispatched agents and awaited client connections, who, in turn, managed trade initiation, API responses, and navigated through balance constraints and concurrent trade executions. The system handles queued trade requests, assigning them promptly as agents became available, and manages incomplete trades, reporting them at the program's conclusion.
