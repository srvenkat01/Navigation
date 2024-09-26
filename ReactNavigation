import logo from './logo.svg';
import './App.css';
import Contact from './Contact';
import {Routes,Route,Link} from 'react-router-dom';
import Home from './Home';
import About from './About';

function App() {
  return (
    
     <div className='container background' >
      <nav>
        <Link to="/">Home</Link> {   ' |'   }
        <Link to="/about">About</Link> {   ' |'   }
        <Link to="/contact">Contact</Link>
      </nav>

      <Routes>
        <Route path="/" element={<Home/>}/>
        <Route path="/about" element={<About/>}/>
        <Route path="/contact" element={<Contact/>}/>
      </Routes>
  
      </div> 
  );
}
export default App;
