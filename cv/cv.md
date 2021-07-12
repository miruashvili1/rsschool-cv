# 1) My name is Giorgi Miruashvili
2) my contact information: my phone numbber is:+995592313051 
                                            instagram:https://www.instagram.com/gio.miruashvili/ 
                                            Discord:GioM#1914
3) Since fourteen year old I have been obssesed by computer programming.I’m too hard-working.I couldn’t afford study officialy and was woking on myself to improve skills for about eight hours in a  day.From books,websites,youtube channels I have studied HTML,CCS,JQUERY,JAVASCRIPT.Of course working only on yourself isn’t enough and it would be a great opportunity for me to study from professional.This course would give me that chance.
I’m highly motivated to take your courses because it would be helpful for my future career path that will be connected to computer programming.Also the skills taking from yours courses would assist me to make my dream come true and build Georgian social networking site.
In 2020 I had worked on two projects  and in a month and a half I made two websites bamigroup.ge and achisari.ge.As you can see I can build a website but I’m perfectionist and always want to be better at me field.

4) My skills: Html,Css,JavaScript,Jquery,ReactJS.
5) One of ReactJS components:
        import {useEffect, useState} from "react";
        import SearchIcon from '@material-ui/icons/Search';

        const Search = ({searchQuery, setSearchQuery, setData}) => {

        const [finalsearch, setFinalsearch] = useState("");

        const handleChange = (e) => {
            setSearchQuery(e.target.value);
        };
        const search = () => {
            setFinalsearch(searchQuery);
        };
        useEffect(() => {
            const products = JSON.parse(localStorage.getItem("products"));
            const res = products.filter((e) => {
            return e.title.toLowerCase().includes(searchQuery.toLowerCase());
            });
            setData(res);
        }, [finalsearch]);

        return (
            <div classNameName={"Search"}>
            <input  className={"Search__input"} type={"search"} placeholder={"Search"} value={searchQuery} onChange={handleChange}/>
            <button  className={"Search__Btn"} type={"submit"} onClick={search}>
                < SearchIcon className={'Search__Btn--Icon'}/>
            </button>
            </div>
        );
        };

        export default Search;

7) I learnt programming languages on my own and I am still studying Gori State University
8) I learnt English at school and also I was studying it for 2 years from the teacher beside school
