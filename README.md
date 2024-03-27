package com.example.ecommerce;

import android.os.Bundle;
import android.widget.ImageView;

import androidx.activity.EdgeToEdge;
import androidx.appcompat.app.AppCompatActivity;
import androidx.core.graphics.Insets;
import androidx.core.view.ViewCompat;
import androidx.core.view.WindowInsetsCompat;

import com.example.ecommerce.databinding.ActivityDashboardBinding;

public class DashboardActivity extends AppCompatActivity {
    ActivityDashboardBinding binding;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
     binding=ActivityDashboardBinding.inflate(getLayoutInflater());
     setContentView(binding.getRoot());
     setSupportActionBar(binding.cart);
}

    private void setSupportActionBar(ImageView cart) {
    }
}
