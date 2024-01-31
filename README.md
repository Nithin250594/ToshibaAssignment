# Building a Frontend Dashboard App with Backend Graph Integration <br/> (Toshiba Assignment)


This task will evaluate your ability to build a complex web app, and design a user-friendly UI based
on provided Figma design.

# Requirements:
<ul>
<li> Frontend: ReactJs and Backend: Nodejs</li>
<li>Design the app's UI based on the Figma design which can be found here.</li>
<li>Entire UI should be static except the Graph Component (Heading name: Growth). Ensure that the
complete UI (except Graph) closely resembles the Figma design in terms of layout, colors, fonts,
and components.</li>
<li>Implement of Graph Component:</li>
<ul>
    <li>The graph should represent the relationship between profit percentage and time from a
large dataset. The dataset comprises two columns:
Timestamp and corresponding Profit Percentage, with a total of 69,681 rows. The
plotted graph should be an interactive one.</li>
    <li>Due to the dataset's size, plotting all data points directly onto a single graph may lead to
performance issues. Hence, an efficient downsampling algorithm is necessary to reduce
the dataset while preserving essential trends. You should implement a downsampling
algorithm (do not use any library) to reduce the dataset size while retaining critical trends
and patterns.</li>
</ul>
</ul>

# Step by step process to complete the task:
1) Identifed List of Components:
    <ul>
    <li>Menu bar</li>
    <li> Dashboard</li>
        <ul>
            <li>Revenue Section (Revenues, Lost deals,  Quarter goal)</li>
            <li> CustomersSection</li>
            <li>Growth section (Graph X-Year & Y-Numbers in 0 to 10K , Top Month, Top year & Top buyer) </li>
            <li> ChatsToNewDeals (Chats, Top states & New deals)</li>
        </ul>
    </ul>
2) Each component elements
    <ul>Menu bar
        <ol>
            <li>Logo</li>
            <li>Input search </li>
            <li> Dashboard (logo)</li>
            <li>Customers (logo) Drop down button : 
            <ul>
                <li>current</li>
                <li>New</li>
                <li>Negotiating</li>   
            </ul>
            </li>
            <li>All reports (logo)</li>
            <li>Geography (logo)</li>
            <li>Conversations</li>
            <li> Details</li>
            <li>Export</li>
            <li>User profie pic, username, postion</li>
            <li>settings</li>
            <li>logout (logo)</li>
        </ol>
    </ul>
    <ul>Top section
    <ol>Revenues Title
        <li>percent and up-arrow icon</li>
        <li>one line paragraph</li>
        <li>one line para and side arrow logo</li>
    </ol>
    <ol>Lost Deals Title
        <li>percent</li>
        <li>one line paragraph</li>
        <li>one line para and side arrow logo</li>
    </ol>
    <ol>Quarter goal Title
        <li>percent graph </li>
        <li>one line para and side arrow logo</li>
    </ol>    
    </ul>

    <ul>
    Middle section
    <ol>
    Customers Title  beside sortby Newest(dropdown)
        <li>list of people details (hover on each person has  four icons  chat, star, edit and 3 dots.</li>
        <li>one line para and side arrow logo</li>
    </ol>
    <ol>
     Growth Section beside sortby Yearly(dropdown)
    <li>Growth graph</li>
    <li>GrowthCard(TopMonth,TopYear,TopBuyer)</li>
    </ol>
    </ul>

















<br/>
<br/>


This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
