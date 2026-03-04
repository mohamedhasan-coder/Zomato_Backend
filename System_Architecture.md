# System Architure: 

                     Client Layer    
   Mobile Application / Web Application / Third Party API 
                        |
                        |  HTTPS (Synchronization)
                        |
                        v
      NGINX (Reverse Proxy)
    SSL Termination | Load Balancer 

              FASTAPI Application
 
   1. AUTH Routes

   2. Resteruant Routes

   3. Orders Route

   4. Realtime Tracking 

   5. Search Routes 

   6. Payment Routes

   7. Review Routes 

   8. Rate Limiter

       |
       |
       |
       V
    (pr) - PG DB, Redis(cache) + Queue, Elastic Search for Searching.