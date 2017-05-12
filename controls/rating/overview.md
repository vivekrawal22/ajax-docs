 protected void RadRating_Rate(object sender, EventArgs e) 
        {
            RadRating rating = (RadRating)sender;
            if (RadRating.Value != 0)
            {
                lblRating.Text = "Current Rating is: " + "<span style='color:Red'>" + RadRating.Value.ToString() + "</span>";
            }
            else
            {
                lblRating.Text = "Rating";
            }

        }
