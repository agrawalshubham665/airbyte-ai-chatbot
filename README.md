# airbyte-ai-chatbot

Learning project to build AI-powered chatbot to interact with e-commerce data.

AI+data application diagram and flow, below:


<img width="223" alt="image" src="https://github.com/user-attachments/assets/a1c38df5-4419-445d-bb70-1c8140f26802" />

# Steps implemented
1. Airbyte Cloud to connect to Stripe test data.
2. Used the Airbyte Postgres Destination connector to send Stripe data to Postgres, deployed on Supabase.
3. Configured Supabase to use PGVector to support embeddings.
4. Created a data pipeline in Airbyte to handle sync tasks and send data embeddings for AI use cases.
5. Created SQL functions to work with openAI question embeddings.
6. Written python-based chatbot uses OpenAI APIs to interact with your data and embeddings.
