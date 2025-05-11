# Task 1: Design the Use Case Diagram of the Features and Functionalities

## Objective

Visualize system interactions by creating a Use Case Diagram that illustrates how users (actors) interact with the Airbnb Clone backend for key functionalities.

## What to Include

* **Actors**: Identify all primary users of the system (e.g., Guest, Host, Admin).
* **Use Cases**: Represent each major feature as an oval (e.g., Register Account, Login, Create Listing, Search Properties, Book Property, Process Payment, Leave Review, Send Message).
* **System Boundary**: Draw a box labeled **Airbnb Clone System** that encloses all use cases.
* **Relationships**: Connect each actor to the use cases they can perform.

## Step-by-Step Instructions (Draw\.io)

1. **Open Draw\.io**

   * Navigate to [https://draw.io](https://draw.io).
   * Click **Create New Diagram**, choose **Blank Diagram**, then **Create**.

2. **Enable UML Shapes**

   * In the left panel, click **More Shapes...**.
   * Under **Software**, check **UML** and click **Apply**.

3. **Add Actors**

   * Drag the **Actor** (stick figure) onto the canvas.
   * Label them **Guest**, **Host**, and **Admin** by double‑clicking each.

4. **Add Use Cases**

   * Drag the **Ellipse** shape (Use Case) onto the canvas.
   * Label each with a feature name:

     * `Register Account`
     * `Login`
     * `Create Listing`
     * `Search Properties`
     * `Book Property`
     * `Process Payment`
     * `Leave Review`
     * `Send Message`

5. **Draw System Boundary**

   * Drag a **Rectangle** around all use cases.
   * Label it **Airbnb Clone System**.

6. **Connect Actors to Use Cases**

   * Select the **Connector** tool.
   * Draw lines from each actor to the use cases they perform:

     * **Guest** → Register Account, Login, Search Properties, Book Property, Process Payment, Leave Review, Send Message
     * **Host** → Login, Create Listing, Process Payment (payout), Send Message, Manage Listings
     * **Admin** → Login, Monitor Platform, Manage Users

7. **Arrange & Style**

   * Align actors on the left and use cases in the center.
   * Use consistent fonts and colors for readability.

8. **Export as PNG**

   * Go to **File → Export As → PNG**.
   * Check **Include a copy of my diagram**, click **Export**, and save as `use_case_diagram.png`.

## Saving to Repository

1. Create a directory named `use-case-diagram/` in your repository.
2. Place this `README.md` and the exported `use_case_diagram.png` inside.

