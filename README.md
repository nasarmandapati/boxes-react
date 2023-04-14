# boxes-react
const Box = props => {
  //  Write your code here.
  const {boxCls, boxText}=props;
  return (
      <div className=(boxCls)>
      <p className="box-text">{boxText}</p>
     </div> 


  );
};

const element = (
  //  Write your code here. 
  <div className="box-bg-con">
      <h1 className="heading">Boxes</h1>
      <div className="box-con">
          <BOX boxCls="box-small" boxText="Small"/>
          <Box boxCls="box-medium" boxText="Medium"/>
          <Box boxCls="box-large" boxText="Large"/>
      </div>
  </div>
);

ReactDOM.render(element, document.getElementById("root"));
