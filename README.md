
# ChainHub


ChainHub is a fullstack decentralized application (dApp) built on the Internet Computer (ICP). It leverages Motoko for the backend logic and modern JavaScript for the frontend, providing a seamless experience for users and developers alike. ChainHub demonstrates how to build, deploy, and interact with canisters both locally and on the mainnet.

## About the App

ChainHub aims to provide a simple yet robust platform for users to interact with blockchain-powered services. The application features:

- **User Authentication:** Secure login system to ensure only authorized users can access personalized features.
- **Dashboard:** A user-friendly dashboard that displays relevant data, user actions, and system status in real time.
- **Motoko Backend:** All business logic and data management are handled by Motoko canisters, ensuring security and decentralization.
- **Modern Frontend:** Built with JavaScript and compatible with frameworks like Vite, the frontend offers a responsive and interactive user interface.

### Key Features

- **Decentralized Authentication:** Users can log in securely, leveraging Internet Identity or other authentication methods.
- **Real-Time Updates:** The dashboard provides live updates and feedback from the backend canister.
- **Easy Deployment:** The project is structured for easy local development and straightforward deployment to the ICP mainnet.

Whether you are a developer looking to learn about Motoko and ICP, or a user interested in decentralized applications, ChainHub provides a solid foundation and example.

## Project Structure

```
ChainHub/
├── backend/                # Motoko backend canister (app.mo)
├── frontend/               # Frontend assets and code
├── src/
│   └── declarations/       # TypeScript/JS canister bindings
├── .dfx/                   # DFX build artifacts (auto-generated)
├── .env                    # Environment variables for DFX
├── dfx.json                # DFX project configuration
├── mops.toml               # Motoko package manager config
├── package.json            # Node.js project config
├── BUILD.md                # Local build and deployment instructions
└── README.md               # Project documentation (this file)
```

<<<<<<< HEAD
## Getting Started

### 1. Prerequisites

- [Node.js](https://nodejs.org/)
- [DFX SDK](https://internetcomputer.org/docs/current/developer-docs/quickstart/local-quickstart)
- [ic-mops](https://docs.mops.one/quick-start#2-install-mops-cli) (Motoko package manager)

### 2. Install Dependencies

```bash
npm install
```

### 3. Start the Local Replica

If you are using DFX v0.28.0 or later, you may need to disable PocketIC for local development.  
Create or edit `~/.config/dfx/settings.json` and add:

```json
{
  "experimental": {
    "pocket_ic": false
  }
}
```

Then start the local replica:

```bash
dfx start --background
```

### 4. Deploy Canisters Locally

```bash
dfx deploy
```

### 5. Run the Frontend

If you are using Vite or another frontend tool, run:

```bash
cd frontend
npm install
npm run dev
```

Open the local frontend URL (usually [http://localhost:5173](http://localhost:5173)) in your browser.

## Example: Calling the Backend

You can call the backend canister from your frontend code like this:

```js
import { backend } from "../src/declarations/backend";

backend.greet("Khushi").then(console.log);
```

## Deploying to Mainnet

To deploy to the Internet Computer mainnet:

```bash
dfx deploy --network ic
```

Make sure you have enough cycles and have set up your identity.

## More Information

- [Motoko Documentation](https://internetcomputer.org/docs/motoko/main/getting-started/motoko-introduction)
- [DFX SDK Docs](https://internetcomputer.org/docs/current/developer-docs/quickstart/local-quickstart)
- [ICP Ninja](https://icp.ninja/) (for quick prototyping)

---


**Happy hacking on ICP!**

---

## Screenshots

Below are screenshots of the main features of ChainHub:

### Dashboard

This image shows the main dashboard, where users can view their data and interact with the app:

<img width="1919" height="958" alt="Dashboard screenshot" src="https://github.com/user-attachments/assets/bcb3487f-1db5-4c9a-8d03-4b65e934df70" />

### Login

This image shows the login screen, where users authenticate to access their personalized dashboard:

<img width="1918" height="952" alt="Login screenshot" src="https://github.com/user-attachments/assets/d2c3baef-9439-4705-8b77-a284a03a5bfd" />

<img width="1919" height="958" alt="image" src="https://github.com/user-attachments/assets/bcb3487f-1db5-4c9a-8d03-4b65e934df70" />

<img width="1918" height="952" alt="image" src="https://github.com/user-attachments/assets/d2c3baef-9439-4705-8b77-a284a03a5bfd" />
=======
### 2. Open the `BUILD.md` file for further instructions.



<img width="1919" height="958" alt="image" src="https://github.com/user-attachments/assets/bcb3487f-1db5-4c9a-8d03-4b65e934df70" />

<img width="1918" height="952" alt="image" src="https://github.com/user-attachments/assets/d2c3baef-9439-4705-8b77-a284a03a5bfd" />
>>>>>>> 74b3c97a9404bb37e2eba3e099f25c816c657451
