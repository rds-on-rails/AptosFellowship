# learn-move

A starter repo with some samples codes to get started with movelang on Aptos
cd into the my-first-dapp root directory, and create a new move directory.

cd into the new move directory and run: aptos move init --name my_todo_list That command creates a sources/ directory and Move.toml file inside the move directory.

In our move directory, run aptos init --network devnet. Press enter when prompted.

Open the Move.toml file.
Add the following code to that Move file, substituting your actual default profile account address from .aptos/config.yaml:
[addresses]
todolist_addr='<default-profile-account-address>'

Create a new todolist.move file within the sources directory and add the following to that file:
let’s try to compile what we have now:

cd into the move directory.
Run: aptos move compile
Run the aptos move test command. If all goes right, we should see a success message like

Now lets setup client.

In the root folder of the my-first-dapp project, run:
npx create-react-app client --template typescript

Run: cd client

Run: npm start

App deployed
https://aptos-fellowship.vercel.app/
